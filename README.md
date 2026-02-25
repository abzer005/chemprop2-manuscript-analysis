# ChemProp2 – Manuscript Analysis and Figure Reproducibility

This repository contains the analysis scripts used to generate the figures and tables for the manuscript:

**"ChemProp2: A Functional Metabolomics Framework to Track Microbiome Drug Metabolism"**

Preprint available at:
[https://doi.org/10.64898/2026.01.30.702925]

---

## Overview

This repository provides reproducible code used for:

- Statistical analyses
- ChemProp2 scoring
- Figure generation
- Table generation

The core ChemProp2 implementation is available at:
[https://github.com/Functional-Metabolomics-Lab/ChemProp-Web-App]

A web-based implementation is available via:
[https://chemprop.gnps2.org/]

---

## Repository Structure

analysis/
│
├── figure1/
├── figure2/
├── figure3/
├── figure4/
├── figure5/
│
└── tables/


Each figure folder contains:

- Scripts used to generate plots
- Intermediate processed data (if applicable)
- Notes describing how the figure was produced

---

## Data Availability

Raw and processed LC–MS/MS datasets used in this study are available via:

- GNPS / MassIVE: [Insert accession number]
- Additional datasets referenced in the manuscript

This repository does not contain raw mass spectrometry data due to file size limitations.

---

## Software and Dependencies

Analyses were performed using:

- Python (version 3.12.2)
- R (version 4.2.2)
- MZmine v4.0.3
- ProteoWizard msconvert(version: 3.0.22031-3c93331, automated build)
---

## Reproducibility Notes

- Figure 1 primarily illustrates conceptual workflow and does not require computational reproduction.
- Figures 2–5 were generated using scripts provided in this repository.
- All statistical analyses follow the procedures described in the Methods section of the manuscript.

Minor adjustments to visualization aesthetics (e.g., label placement, formatting) may differ slightly depending on software versions.

---

## License

This repository is distributed under the BSD 3-Clause License.  
See the LICENSE file for details.
