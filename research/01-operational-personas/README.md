# Research Track 01: Operational Persona Engineering

## Focus
Deconstructing nominal prompting and formalizing operational persona engineering via mathematical boundary conditions, negative constraints, and epistemic stances.

## Core Pillars
- **The Nominal Fallacy**: Why prepending `"You are an expert"` fails to alter computational capacity.
- **The 7-Tuple Persona Model**: Formalizing $\mathcal{P} = \langle \mathcal{I}, \mathcal{E}, \mathcal{K}, \mathcal{H}, \mathcal{T}, \mathcal{R}, \mathcal{S} \rangle$.
- **Adversarial Epistemic Stance ($`\mathcal{E}_{\text{adv}}`$)**: Counteracting the base model's default affirmative bias.
- **The Logit Masking Realization Law**: Distinguishing finite negative logit shifts ($`\Delta z_v \ll 0`$) from external hard constraints ($`z_v = -\infty`$).

## Primary Documents & Specs
- Whitepaper: [`../../papers/operational-personas/personas_research.md#layer-1`](../../papers/operational-personas/personas_research.md)
- Formal Spec: [`../../specs/7-tuple-persona-spec.md`](../../specs/7-tuple-persona-spec.md)
