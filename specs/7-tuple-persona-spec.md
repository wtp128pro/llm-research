# Formal Specification: Operational Persona 7-Tuple ($\mathcal{P}$)

## Mathematical Definition

An Operational Persona is defined as a closed 7-tuple:

$$
\mathcal{P} = \langle \mathcal{I}, \mathcal{E}, \mathcal{K}, \mathcal{H}, \mathcal{T}, \mathcal{R}, \mathcal{S} \rangle
$$

Unlike nominal prompts ("You are an expert"), an operational persona functions as a strict boundary condition in the continuous dynamical system of the transformer's latent space.

---

## The 7 Elements

### 1. Identity & Scope Boundary ($\mathcal{I}$)
- **Domain Specialization**: Explicit, bounded functional domain.
- **Negative Boundary (Anti-Scope)**: Explicit declaration of domains and decisions the persona is strictly forbidden from evaluating.
- **Epistemic Humility Rule**: Rejection of questions falling outside the defined operational envelope.

### 2. Epistemic Stance ($\mathcal{E}$)
- **Adversarial Verification Stance ($``\mathcal{E}_{\text{adv}}``$)**: Default prior assuming incoming artifacts contain latent concurrency races, input gaps, or unhandled failures until proven otherwise.
- **Suppression of Affirmative Bias**: Mathematical counter-pressure against the base model's RLHF sycophancy prior.
- **Asymmetric Verification**: Aligned with Popperian falsification—a single invariant violation falsifies the entire proposal.

### 3. Non-Negotiable Invariants ($``\mathcal{K} = \mathcal{K}_{\text{det}} \cup \mathcal{K}_{\text{neural}}``$)
- **Deterministic Invariants ($``\mathcal{K}_{\text{det}}``$)**: Rules verifiable via deterministic tooling (type-checkers, compilers, AST parsers, linters).
- **Neural Invariants ($``\mathcal{K}_{\text{neural}}``$)**: Semantic properties requiring transformer contextual evaluation (e.g., distributed state isolation, architectural boundary preservation).
- **Enforcement Principle**: Any violation of an invariant in $\mathcal{K}$ triggers an automatic blocking veto ($\text{Sev-1}$).

### 4. Adversarial Attack Heuristics ($\mathcal{H}$)
- **Targeted Falsification Probes**: Structured checklists of domain-specific failure modes.
- **Stress-Test Vectors**:
  - Concurrency & race conditions (TOCTOU, lock ordering, thread starvation).
  - Structural boundary cases (empty sets, unbounded inputs, MTU overflow).
  - Malicious payloads & prompt injection attempts.

### 5. Permitted Tool Matrix ($\mathcal{T}$)
- **Deterministic Tool Bindings**: Out-of-band execution tools (AST linters, SAT solvers, diff parsers).
- **Least-Privilege Invocation**: Tools executed out-of-band via decoupled agentic harnesses, never conflated with in-context generation.

### 6. Strict Output Schema ($\mathcal{R}$)
- **Structured Representation**: Machine-parseable JSON/XML schemas enforcing validation before acceptance.
- **Required Fields**:
  - `verdict`: `APPROVED` | `REJECTED_WITH_INVARIANTS` | `HALTED_INPUT_GAP`.
  - `invariant_violations`: Array of violated invariant identifiers, severity ratings, and proof counterexamples.
  - `input_gaps`: Array of missing architectural specifications preventing safe review.

### 7. Quantitative Confidence & Severity Scoring ($\mathcal{S}$)
- **Severity Ranking**: Strict monotonic ordering: $``\text{Sev-1} > \text{Sev-2} > \text{Sev-3} > \text{Sev-4}``$.
- **Severity-Over-Majority Law**:
  

$$
\text{Final Verdict} = \begin{cases} \text{BLOCK}, & \exists i \in \mathcal{A} \text{ s.t. } \text{Severity}(i) = \text{Sev-1} \\\\ \text{Consensus}(\mathcal{A}), & \text{otherwise} \end{cases}
$$

---

## Logit Masking Realization Law

1. **In-Context Negative Constraints**: Provide finite logit attenuation ($``\Delta z_v \ll 0``$), driving $P(v) \to 0$ without guaranteeing mathematical impossibility.
2. **Deterministic Hard Clamping**: Strict logit masking ($``z_v = -\infty``$) requires external runtime decoding constraints (CFG decoders, regex masks, JSON grammar validators).
