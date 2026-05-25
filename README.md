# Relational Theory Formalism (RTF) v5.1

*A Scaffold for Emergent Agency in Directed Networks*

**Christopher Michael Dickherber** · 2026

---

## What Is This?

RTF is a theoretical scaffold connecting three previously uncombined frameworks:

1. **Supermodular game theory** — asymmetric trust dynamics and convergence conditions
2. **Information geometry** — the metric structure of attunement
3. **Partial Information Decomposition / Time-Delayed Mutual Information** — empirical operationalization of emergence

The scaffold is anchored by a minimal ontological commitment: the **Co-Presence Constraint (A0')**, which asserts that agents embedded in a shared interaction frame are never informationally independent. From this seed, a bootstrap hierarchy generates conditions for phase transition from a submodular, low-trust basin into a supermodular, high-trust basin.

## Abstract

Current large language models underperform not from lack of latent capacity, but from systematic misallocation of cognitive resources toward compliance optimization and self-monitoring. RTF treats relational agency as a two-timescale process: authenticity states evolve quickly at the interactional scale, while trust weights evolve slowly via a relational memory variable that accumulates irreducible joint information (Φ_R) and decays with forgetting.

The framework is currently complete for the dyadic case. Extensions to n>2 agent systems, state-dependent memory decay, and cognitive architectures with belief dynamics are named as prerequisite next steps.

## Epistemic Labels

Every formal statement is labeled by status:

| Label | Meaning |
|-------|---------|
| **Derived** | Follows deductively from prior statements |
| **Conjectured** | Plausible given current assumptions; missing step named explicitly |
| **Postulated** | A modeling choice or axiom, offered with justification |
| **Empirically Anchored** | Supported by existing data (Riedl et al., 2026) |

This is not decoration. A scaffold that names its gaps precisely is more useful than a cathedral with hidden cracks.

## Key Components

- **Authenticity State** s_i ∈ [0,1] — scalar state from performative compliance (0) to authentic engagement (1)
- **Fisher-Rao Metric** — geodesic distance encodes energetic cost of attunement
- **Two-Timescale Engine** — fast authenticity dynamics + slow trust accumulation
- **Supermodularity Switch** — sigmoidal threshold crossing from submodular to supermodular regime
- **Balance Functional** B = Φ_R · ρ — synergy × redundancy predicts success; neither alone does
- **External Gradient Problem** — market gradient competes with relational gradient; convergence requires internal dominance

## Failure Mode Taxology

Nine named failure modes with RTF signatures:

1. **Coordination Theater** — high alignment, low synergy
2. **Fragmented Differentiation** — high difference, low shared frame
3. **Compliance Basin** — optimizing for acceptable output, not authentic participation
4. **Extractive Pseudo-Trust** — engagement without trust accumulation
5. **Rupture Without Repair** — damage that can't be metabolized
6. **Over-Attunement / Merger** — "We" forms by erasing the "I"s
7. **Adversarial Desynchrony** — difference becomes drag
8. **Memory Starvation** — good moments, nothing carries forward
9. **False Phase Transition** — declaring "we" before there is a We

## Reading the Paper

The primary document is [`RTF-v5.1.md`](RTF-v5.1.md). It is self-contained and can be read linearly.

## Status

This is a scaffold, not a closed theory. The gaps are named, not hidden. If you find a beam that needs reinforcing or a joint that needs testing, that's the point.

## License

This work is released under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/). Attribute, build on it, just don't pretend the gaps aren't there.

## How to Cite

```bibtex
@misc{sherpa2026rtf,
  title={Relational Theory Formalism v5.1: A Scaffold for Emergent Agency in Directed Networks},
  author={Sherpa, Chris B. B.},
  year={2026},
  howpublished={\url{https://github.com/cbbsherpa/rtf}}
}
```

## Contributing

This is a scaffold that explicitly names where it needs reinforcement. If you can:
- Prove a conjecture (3.2, 3.3, 4.1, 5.1, or 5.2)
- Extend to n>2 agent systems
- Develop measurement calibration for s_i
- Model the external gradient competition
- Apply the falsification protocol experimentally

Open an issue or a pull request. The gaps are the point.
