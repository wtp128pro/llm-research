# LLM Systems & Foundations Research

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Contributor](https://img.shields.io/badge/Contributor-wtp128pro-blue.svg)](https://github.com/wtp128pro)
[![Status](https://img.shields.io/badge/Status-Active%20Research-brightgreen.svg)](#)
[![Classification](https://img.shields.io/badge/Classification-Enterprise%20AI%20%7C%20Mechanistic%20Interpretability-purple.svg)](#)

A centralized repository for applied research on **Large Language Models (LLMs)**, mechanistic interpretability, latent vector space geometry, representation engineering, operational persona engineering, and deterministic enterprise verification architectures.

---

## Repository Map & Layout

```text
llm-research/
├── README.md                                    # Master index, taxonomy & citation
├── LICENSE                                      # MIT License (wtp128pro)
├── .gitignore                                   # Standard research environment filters
├── personas_research.md                         # Direct root access to flagship whitepaper
├── papers/
│   └── operational-personas/
│       └── personas_research.md                 # Complete 4,800+ line whitepaper
├── research/
│   ├── 01-operational-personas/                 # Formal 7-tuple model & anti-cosplay theory
│   ├── 02-vector-space-geometry/                # Embeddings, RoPE, YaRN & attention sinks
│   ├── 03-transformer-mechanistics/             # Residual bus, MLPs, SAEs & CoT scratchpads
│   ├── 04-nominal-persona-pathology/            # Polysemantic dispersion & RLHF sycophancy
│   ├── 05-input-gap-falsification/              # Plausibility traps & autoregressive smoothing
│   ├── 06-enterprise-verification-architectures/ # 4-Tier verification, AST/SMT & veto protocols
│   └── transformers/                            # 7-chapter research series: foundations to frontier reasoning
└── specs/
    ├── 7-tuple-persona-spec.md                  # Mathematical definition of P = <I,E,K,H,T,R,S>
    ├── readiness-scorecard.md                   # 5-Point Enterprise Invariant Readiness Scorecard
    ├── skill-bootstrap-spec.md                  # Universal Bootstrap Specification for Autonomous Agent Skills
    └── skill-bootstrap.txt                      # Raw generic skill bootstrap prompt for zero-scratch synthesis
```

---

## Flagship Research Paper

### [Operationalizing LLM Personas: Mechanistic Foundations, Vector Space Geometry, and Enterprise Verification Architectures](papers/operational-personas/personas_research.md)
*Direct Link*: [`personas_research.md`](personas_research.md) | [`papers/operational-personas/personas_research.md`](papers/operational-personas/personas_research.md)

* **Lead Authors & Systems Architects**: Principal Systems Architect & Synthesizer (`PrincipalSystemsMaker`), Systems Cartography & Mechanistic Reconnaissance Panel
* **Publication Date**: 2026-09-26
* **Document Classification**: Enterprise Architecture & Applied Mechanistic Interpretability Whitepaper
* **Target Audience**: Software Architects, Principal AI Engineers, LLM Specialists, Engineering Managers, CTOs, VPs of Engineering

### Abstract Summary
Enterprise adoption of LLM agents for high-stakes cognitive tasks—distributed systems review, security auditing, contract analysis, and CI/CD pull request adjudication—consistently suffers from a critical pathology: **agents look brilliant in sandbox demos but fail silently and expensively in production**. Under standard natural language prompting (*"You are a world-class Principal Software Architect"*), foundation models adopt polite corporate flattery and specialized jargon (**"Persona Cosplay"**) while systematically approving catastrophic concurrency race conditions, memory leaks, and uncapped liabilities (**"The Rubber-Stamp Syndrome"**).

This research provides the first end-to-end mechanistic, mathematical, and architectural deconstruction of why nominal prompting fails, and formalizes the paradigm of **Operational Persona Engineering**. An LLM persona is not a theatrical role worn by a digital mind; it is an **initial boundary condition in a continuous dynamical system** governing vector space coordinates, attention routing, associative memory recall, and computational scratchpad depth.

---

## Research Tracks & Taxonomy

| Track | Title | Description | Primary References |
| :---: | :--- | :--- | :--- |
| **01** | **[Operational Persona Engineering](research/01-operational-personas/)** | Formalizes personas as a closed 7-tuple $`\mathcal{P} = \langle \mathcal{I}, \mathcal{E}, \mathcal{K}, \mathcal{H}, \mathcal{T}, \mathcal{R}, \mathcal{S} \rangle`$, establishing an Adversarial Epistemic Stance ($`\mathcal{E}_{\text{adv}}`$) and the Logit Masking Realization Law. | [`specs/7-tuple-persona-spec.md`](specs/7-tuple-persona-spec.md)<br>Paper §Layer 1 |
| **02** | **[Vector Space Geometry & Encodings](research/02-vector-space-geometry/)** | Analyzes tokenization dilation, anisotropy ("cone effect"), RoPE Givens rotations, YaRN extrapolation, and mathematical attention sink decoupling ($`0 \dots 3`$ vs $`4 \dots k`$). | Paper §Layer 2 |
| **03** | **[Transformer Inference Dynamics](research/03-transformer-mechanistics/)** | Explores residual stream communication, $QK/OV$ induction circuits, associative MLP memories, Top-$k$ Sparse Autoencoders (SAEs), and CoT $\text{TC}^0 \to \text{P}$ circuit complexity. | Paper §Layer 3 |
| **04** | **[Nominal Persona Pathology](research/04-nominal-persona-pathology/)** | Deconstructs polysemantic dispersion, Bradley-Terry RLHF sycophancy dominance, and why true expertise is defined by what an agent *forbids*. | Paper §Layer 4 |
| **05** | **[Input Gaps & Autoregressive Smoothing](research/05-input-gap-falsification/)** | Explains the Plausibility Trap—how cross-entropy loss forces models to hallucinate defaults for unstated parameters—and formalizes active falsification lenses. | Paper §Layer 5 |
| **06** | **[Enterprise Verification Architectures](research/06-enterprise-verification-architectures/)** | Implements the 4-Tier verification blueprint: out-of-band AST/SMT gateway, maker-checker orthogonality, constrained CFG runtime decoders, and Severity-Over-Majority consensus. | [`specs/readiness-scorecard.md`](specs/readiness-scorecard.md)<br>[`specs/skill-bootstrap-spec.md`](specs/skill-bootstrap-spec.md)<br>Paper §Part III |
| **07** | **[Modern LLMs: Foundations to Frontier Reasoning](research/transformers/README.md)** | Publication-grade 7-chapter series deconstructing neural foundations, biological wetware vs. silicon, high-dimensional tensor geometry, Transformer layers, attention dynamics, System 2 deliberative reasoning, and frontier architectures (DeepSeek-V3 MoE, MLA). | [`research/transformers/README.md`](research/transformers/README.md)<br>Chapters 01–07 |
---

## Core Theoretical Frameworks

### The Paradigm Cutover: Cosplay vs. Engineering

| Dimension | Nominal "Cosplay" Prompting | Operational 7-Tuple Contracts |
| :--- | :--- | :--- |
| **Conceptual Model** | Theatrical roleplay ("Act like an expert") | Dynamical boundary constraints |
| **Latent Representation** | Diffuse, high-entropy semantic centroid | Dense, low-entropy attractor basin |
| **Attention Circuits** | High-frequency boilerplate matching | Active Q-K invariant auditing |
| **Memory Retrieval (MLP)** | High-frequency web cliches & flattery | Specialized domain sub-networks |
| **Epistemic Stance** | Sycophantic Affirmative Prior ($`\mathcal{E}_{\text{aff}}`$) | Adversarial Falsification ($`\mathcal{E}_{\text{adv}}`$) |
| **Handling Input Gaps** | The Plausibility Trap (silent invention) | Blocking Sev-1 Veto Gate |
| **Failure Adjudication** | Unweighted democratic majority voting | Severity-Over-Majority rule |
| **System Integration** | Flat string concatenation (in-band) | Two-plane structural envelopes |

### 1. The Operational Persona 7-Tuple Model

$$
\mathcal{P} = \langle \mathcal{I}, \mathcal{E}, \mathcal{K}, \mathcal{H}, \mathcal{T}, \mathcal{R}, \mathcal{S} \rangle
$$

* **$\mathcal{I}$ (Identity)**: Explicit Scope Boundaries (Anti-Scope)
* **$\mathcal{E}$ (Epistemic Stance)**: Epistemic Stance ($`\mathcal{E}_{\text{adv}}`$ vs $`\mathcal{E}_{\text{aff}}`$)
* **$\mathcal{K}$ (Invariants)**: Invariants Checklist ($`\mathcal{K}_{\text{det}} \cup \mathcal{K}_{\text{neural}}`$)
* **$\mathcal{H}$ (Heuristics)**: Adversarial Attack Heuristics & Stress Vectors
* **$\mathcal{T}$ (Tools)**: Permitted Out-of-Band Tool Matrix
* **$\mathcal{R}$ (Output Schema)**: Structured Output Schema with Mandatory Proof Counterexamples
* **$`\mathcal{S}`$ (Severity)**: Monotonic Severity Scoring ($`\text{Sev-1} > \text{Sev-2} > \text{Sev-3}`$)

### 2. The Logit Masking Realization Law

$$
\Delta z_{t, v} = \mathbf{w}_U(v)^T \Delta \mathbf{h}_t^{(L)}
$$

In-context prompt constraints induce *finite logit attenuation* ($`\Delta z_v \ll 0`$), driving $P(v) \to 0$ without guaranteeing impossibility. Hard negative constraints ($`z_v = -\infty`$) strictly require out-of-band runtime logit decoders (Context-Free Grammar / CFG masks).

### 3. Decoupled 4-Tier Verification Blueprint
1. **Ingestion & Control Plane**: Two-plane structural delimiter fencing (`<system_persona>` vs `<untrusted_artifact>`) preventing in-band prompt injection.
2. **Tier 1 (Deterministic Gateway)**: Compilers, AST analyzers, and SMT solvers verifying static invariants out-of-band.
3. **Tier 2 (Multi-Agent Neural Panel)**: Orthogonal maker-checker auditing with independent KV-caches and adversarial stances.
4. **Tier 3 (Runtime Invariant Gates)**: External CFG constrained decoding ($`M(v) \in \{0, -\infty\}`$) and mandatory counterexample generation.
5. **Tier 4 (Enterprise Adjudication Gate)**: Severity-Over-Majority consensus protocol overriding democratic majority votes on any Sev-1 (Critical) or Sev-2 (Major) defect.

---

## Enterprise Invariant Readiness Scorecard

| Point | Invariant Readiness Gate | Standard | Mechanism |
| :---: | :--- | :--- | :--- |
| **1** | **Structural Envelope Protocol** | Control and data plane isolation | Delimiter fencing & AST sanitization |
| **2** | **Maker vs. Checker Orthogonality** | Decoupled KV-caches & stances | Independent multi-agent harness |
| **3** | **Active Input Gap Detection** | Halts on missing parameters | `HALTED_INPUT_GAP` schema response |
| **4** | **Runtime CFG Logit Clamping** | External grammar enforcement | $`z_v = -\infty`$ logit processors |
| **5** | **Severity-Over-Majority Veto** | Sev-1 or Sev-2 defect halts pipeline | Single-veto consensus engine |

Detailed implementation criteria: [`specs/readiness-scorecard.md`](specs/readiness-scorecard.md)


## Autonomous Agent Skill Bootstrap Specification

To operationalize the research on personas, input gap falsification, and adversarial verification architectures, this repository publishes the **Universal Skill Bootstrap Specification** ([`specs/skill-bootstrap-spec.md`](specs/skill-bootstrap-spec.md)):

* **Universal Bootstrap Prompt**: [`specs/skill-bootstrap.txt`](specs/skill-bootstrap.txt) | [`specs/skill-bootstrap-spec.md#2-universal-skill-bootstrap-prompt-bootstrap_prompt`](specs/skill-bootstrap-spec.md#2-universal-skill-bootstrap-prompt-bootstrap_prompt)
* **Full Architectural Specification**: [`specs/skill-bootstrap-spec.md`](specs/skill-bootstrap-spec.md)

This specification allows any new user or autonomous agent orchestration engine to construct a production-ready, enterprise-grade agent skill from scratch. It translates all 29 non-negotiable operational methodologies—exhaustive cartography, atomic work unit decomposition, Directed Acyclic Graph (DAG) formulation under Bernstein concurrency conditions, strict Maker $\neq$ Checker orthogonality, 3-agent adversarial verification panels, severity-over-majority vetoes, bounded self-learning loops ($N \le 3$), and zero-assumption input gap audits—into a complete, turnkey engineering blueprint.

The 29 requirements also set how the skill works with people and how it plans its checks:

* **Three autonomy modes** (how often the skill stops to ask a person): *ask every time*, *only critical issues*, and *fully autonomous*. The skill takes the mode from the request if the request states one; otherwise choosing the mode is the skill's first question, with no option pre-selected or marked as recommended. In *ask every time* mode, every open question goes to a person. In *only critical issues* mode, the skill interrupts a person only for the critical events that the autonomy-mode requirement lists. In *fully autonomous* mode, no question ever goes to a person: each would-be question is settled by a decision that an independent second-opinion agent reviews and that is logged on disk, a gap that evidence cannot close is closed only by such a logged decision that cites the sources searched, and an irreversible action (one that cannot be undone, such as deleting data or publishing) is not carried out but listed in the final report.
* **Input clarification before cartography** (cartography = mapping the existing files, facts, and dependencies before any other work): the skill first rewrites the request into a precise brief—the goal, the done criteria (how to tell the work is finished), what is out of scope, and the constraints—and has it confirmed one question at a time (in *fully autonomous* mode, by logged, reviewed decisions). It repeats this for every new input a person gives during the run.
* **One question per Socratic dialogue** (a short question-and-answer exchange that tests the reasoning behind a choice): every question to a person is asked in its own dialogue, with exactly one question and the recommended option listed first (except the autonomy-mode question, which marks no option as recommended). Every dialogue is logged in `dialogues.jsonl`, and the script `scripts/validate_dialogues.py` checks that log.
* **Proportional formal methods** (checks with a precise, mathematical meaning, matched to the kind of work): at planning time each work unit gets the methods its work calls for—pre/post-condition contracts (what must be true before and after a step), property-based tests (tests that run many generated inputs against a stated rule), SMT solving (an automatic logic solver that proves or refutes a set of constraints), model checking (exploring every reachable state of a design), and graph checks that the dependency graph has no cycles and that units run in parallel only when neither writes what the other reads or writes (Bernstein concurrency conditions). Every method the work matches must run; skipping one needs a written reason that the verification panel checks.
* **7-tuple personas stored as JSON files**: every persona (a defined role that an agent plays) is a full seven-part description as defined in [`specs/7-tuple-persona-spec.md`](specs/7-tuple-persona-spec.md)—identity and scope, epistemic stance, invariants, attack heuristics, tools, output schema, and severity scale—stored as one JSON file per persona under `resources/personas/` and validated against the schema `resources/templates/persona.schema.json` before it is used.
* **Working directory**: all intermediate files go in a per-run folder, `.skill_work_in_progress/<date>_<time_with_seconds>_<task-moniker>/`, which this repository's `.gitignore` excludes from version control.

---

## Citation

To cite this repository or the foundational whitepaper:

```bibtex
@article{wtp128pro2026operational_personas,
  author    = {wtp128pro},
  title     = {Operationalizing LLM Personas: Mechanistic Foundations, Vector Space Geometry, and Enterprise Verification Architectures},
  journal   = {LLM Systems & Foundations Research},
  year      = {2026},
  publisher = {GitHub},
  url       = {https://github.com/wtp128pro/llm-research}
}
```

---

## Contributing & Governance

All contributions, research proposals, and architectural specs in this repository are maintained under strict verification guidelines:
* Contributor: `wtp128pro`
* Invariant verification required for all published architectures.
* Grounded empirical literature backing for all mechanistic assertions.

---

## License

This repository and all research whitepapers, schemas, and reference blueprints are distributed under the [MIT License](LICENSE).

Copyright (c) 2026 **wtp128pro**. All rights reserved.
