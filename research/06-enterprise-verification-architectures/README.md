# Research Track 06: Decoupled Multi-Agent Enterprise Verification Architectures

## Focus
Production architectures that enforce structural isolation, out-of-band deterministic gating, invariant checking, and robust consensus.

## Core Pillars
- **4-Tier Structural Blueprint**:
  - *Ingestion Plane*: Two-plane structural envelope (`<system_persona>` vs `<untrusted_artifact>`) neutralizing in-band prompt injections.
  - *Tier 1 (Deterministic Gateway)*: AST parsers, compilers, and SMT solvers verifying static invariants before LLM invocation.
  - *Tier 2 (Adversarial Multi-Agent Panel)*: Maker vs. Checker orthogonality with strictly decoupled KV-caches and adversarial stances.
  - *Tier 3 (Runtime Invariant Gates)*: Grammar-constrained decoding (CFGs) and automated counterexample falsification.
  - *Tier 4 (Adjudication Gate)*: Severity-Over-Majority consensus protocol ensuring a single Sev-1 defect halts deployment.
- **In-Band CI/CD Prompt Injection Defense**: Delimiter fencing and entity escaping for untrusted diff ingestion.

## Primary Documents & Specs
- Whitepaper: [`../../papers/operational-personas/personas_research.md#part-iii`](../../papers/operational-personas/personas_research.md)
- Readiness Scorecard: [`../../specs/readiness-scorecard.md`](../../specs/readiness-scorecard.md)
