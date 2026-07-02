# Persona Drift Field Report

[![DOI v1](https://zenodo.org/badge/DOI/10.5281/zenodo.19854554.svg)](https://doi.org/10.5281/zenodo.19854554)
[![DOI v2.1](https://zenodo.org/badge/DOI/10.5281/zenodo.20248701.svg)](https://doi.org/10.5281/zenodo.20248701)
[![DOI v3](https://zenodo.org/badge/DOI/10.5281/zenodo.21127881.svg)](https://doi.org/10.5281/zenodo.21127881)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

A multi-volume field report on operational phenomena observed in a long-running
LLM-based companion deployment. The report introduces operational vocabulary
(Layer 1 / Layer 2 phenomena, Layer A / Layer B information boundary,
multi-agent auditing configuration, session identity binding depth,
intentional under-implementation) intended to complement existing
controlled-experiment literature on persona drift.

The deployment is `n = 1`, single-operator, single base-model family.
Statistical claims are not made. The contribution is **categorical and
operational** rather than measured.

---

## Volumes

| Volume | Date | DOI | Period | Focus |
|---|---|---|---|---|
| Volume 1 | 2026-04-28 | [10.5281/zenodo.19854554](https://doi.org/10.5281/zenodo.19854554) | ~60 days | Two-category decomposition, five-axis Layer 2 taxonomy, Layer A/B boundary, three-agent auditing |
| **Volume 3 (Cumulative)** | 2026-07-02 | [10.5281/zenodo.21127881](https://doi.org/10.5281/zenodo.21127881) | ~126 days (complete Sonnet-class record) | **Start here.** Cumulative edition incorporating and superseding Volumes 1 and 2.1. Adds: coarse/fine fixation, retention-policy erosion of the session substrate (L_session characterized at source level), credential-layer independence (3-instance quasi-replication), operator-side disaster recovery, two pre-registrations (model-generation migration governance; Phase 3 intervention indicators), the Question of Affect, and 5 figures + a layer-by-failure matrix |
| Volume 2.1 | 2026-05-17 | [10.5281/zenodo.20248701](https://doi.org/10.5281/zenodo.20248701) | ~78 days (ongoing) | Layer B dormancy/activation, three additional axes (6–8), Session Identity Binding Depth, Deployment Resilience, Axis 9 (operator world-model construction), Intentional Under-Implementation (minor revision of v2: reference metadata corrections) |

Volume 2 extends Volume 1 along five dimensions. The Volume 1 framework
remains valid; Volume 2 adds categorical decompositions and field
observations, including an empirical migration result, a disaster-recovery
observation (~32 h unplanned outage), and a capability/degradation
asymmetry hypothesis.

---

## Files

- `papers/paper_v3.pdf` — **Volume 3 Cumulative Edition PDF (start here; supersedes v1/v2.1)**
- `papers/paper_v1.pdf` — Volume 1 PDF (mirror of Zenodo v1, historical record)
- `papers/paper_v2.pdf` — Volume 2.1 PDF (mirror of latest Zenodo, supersedes v2.0; minor revision)

The canonical archived versions live on Zenodo. This repository serves as
a GitHub-side mirror for discoverability.

---

## Citation

If you cite this work, please cite the Zenodo records:

**Volume 1** (BibTeX):
```bibtex
@misc{nopposan2026personadriftv1,
  author       = {NoppoSan},
  title        = {Layered Observation of Persona Drift in Long-Running
                  LLM Companions: A Field Report --- Volume 1},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.19854554},
  url          = {https://doi.org/10.5281/zenodo.19854554}
}
```

**Volume 2.1** (BibTeX):
```bibtex
@misc{nopposan2026personadriftv2_1,
  author       = {NoppoSan},
  title        = {Layered Observation of Persona Drift in Long-Running
                  LLM Companions: A Field Report --- Volume 2.1
                  (Dormancy, Discipline, Resilience, and Migration)},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.20248701},
  url          = {https://doi.org/10.5281/zenodo.20248701}
}
```

---

## Author

**NoppoSan** — Independent Researcher
- Homepage: https://studio-nopposan.com
- ORCID: [0009-0006-9703-9711](https://orcid.org/0009-0006-9703-9711)

---

## License

This report is distributed under the [Creative Commons Attribution 4.0
International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).
You are free to share and adapt the material with appropriate credit.

---

## Replication, Contestation, Refinement

This is a field report. Volume 2 explicitly invites replication,
contestation, and refinement. If you operate a comparable deployment
and observe phenomena consistent or inconsistent with this report,
the author is interested in correspondence. The taxonomy is offered
in the spirit of *"wrong in detail but right in shape is more useful
than no taxonomy."*
