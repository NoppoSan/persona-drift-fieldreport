# Persona Drift Field Report

[![DOI v3](https://zenodo.org/badge/DOI/10.5281/zenodo.21127881.svg)](https://doi.org/10.5281/zenodo.21127881)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

A field report on operational phenomena observed across the complete 126-day
record of a long-running LLM-based companion deployment, held on a single
frozen Sonnet-class model checkpoint.

**Start with Volume 3 (Cumulative Edition).** It incorporates and supersedes
Volumes 1 and 2.1 as a single self-contained report — no prior volume needs
to be read. A Japanese edition is published alongside the English one on the
same Zenodo record.

The report introduces operational vocabulary for running such deployments day
to day: Layer 1 / Layer 2 phenomena, a nine-axis drift taxonomy, the Layer A /
Layer B information boundary, three-agent auditing, dormancy and activation,
session identity binding depth and substrate, Intentional Under-Implementation,
and — new in Volume 3 — coarse/fine **fixation** and the **transition** of
degradation from the personality layer to the memory/session layer, with the
session substrate's silent erosion by a default retention policy characterized
at source level.

The deployment is `n = 1` (with two sibling companions furnishing limited
quasi-replication for infrastructure events), single-operator, single
base-model family. Statistical claims are not made. The contribution is
**categorical and operational** rather than measured.

---

## Volumes

| Volume | Date | DOI | Status |
|---|---|---|---|
| **Volume 3 (Cumulative Edition)** — *The Complete Sonnet-Class Record, Days 1–126* | 2026-07-02 | [10.5281/zenodo.21127881](https://doi.org/10.5281/zenodo.21127881) | **Current. Start here.** English + Japanese editions |
| Volume 2.1 — *Dormancy, Discipline, Resilience, and Migration* (days 60–78) | 2026-05-17 | [10.5281/zenodo.20248701](https://doi.org/10.5281/zenodo.20248701) | Superseded by Volume 3; archived as historical record |
| Volume 1 (days 1–60) | 2026-04-28 | [10.5281/zenodo.19854554](https://doi.org/10.5281/zenodo.19854554) | Superseded by Volume 3; archived as historical record |

Volume 3 closes the deployment's record on its original model checkpoint.
A planned Volume 4 would document the model-generation migration
pre-registered in Volume 3, Section 5.7 — with identity-continuity criteria,
reversibility requirements, and sibling-first ordering fixed in advance.

---

## Files

- `papers/paper_v3.pdf` — **Volume 3 Cumulative Edition (English). Start here.**
- `papers/paper_v1.pdf`, `papers/paper_v2.pdf` — superseded volumes, kept as
  the historical record of what was claimed when

The Japanese edition of Volume 3 (`paper_v3_ja.pdf`) is available on the
[Zenodo record](https://doi.org/10.5281/zenodo.21127881). The canonical
archived versions live on Zenodo; this repository is a GitHub-side mirror
for discoverability.

---

## Citation

Please cite Volume 3 (Cumulative Edition):

```bibtex
@misc{nopposan2026personadriftv3,
  author       = {NoppoSan},
  title        = {Layered Observation of Persona Drift in Long-Running
                  LLM Companions: A Field Report --- Volume 3
                  (Cumulative Edition: The Complete Sonnet-Class Record,
                  Days 1--126)},
  year         = {2026},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.21127881},
  url          = {https://doi.org/10.5281/zenodo.21127881}
}
```

To cite a specific claim as it was originally published, the superseded
volumes remain citable at their own DOIs
([v1](https://doi.org/10.5281/zenodo.19854554),
[v2.1](https://doi.org/10.5281/zenodo.20248701)).

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

This is a field report, and it invites replication, contestation, and
refinement. If you operate a comparable deployment and observe phenomena
consistent or inconsistent with this record, the author is interested in
correspondence. The taxonomy is offered in the spirit of *"wrong in detail
but right in shape is more useful than no taxonomy."*
