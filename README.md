# Purpose of this Repository
This repository contains links to all resources relevant for the SIGMOD 2023 Submission "Role Matching in Temporal Data"

## Code
* Main Implementation in scala. Implements EM,CBRB (with and without decay),CQM,TSM,VSM as well as various data exports and transformations to exchange data between the different programming languages: https://github.com/leonbornemann/CompatibilityBasedRoleMatching/
* Evaluation and Plots via Jupyter Notebooks: https://github.com/leonbornemann/RoleMatchingEvaluation/
* Implementation (in go) of RM: https://github.com/leonbornemann/LSHEnsembleForRoleMatching/

## Datasets
* Source for raw Wikipedia version history data: https://dumps.wikimedia.org/
* Full extracted Role Datasets (ED,FO,MI,PO,TV): [Available here](https://drive.google.com/file/d/1hGYpBeJrgzoOQaLT9JjCIROeV_sTQZBS/view?usp=sharing)
* Uniform sample of 1 million pairs (per dataset) of roles in 1TVA: [Available here](https://drive.google.com/file/d/16J1yGQmjwUJu-k58x0DvIcRWy2r4OgsM/view?usp=sharing), variants with missing data [Available here](https://drive.google.com/file/d/1TmdZZ1hdEw3HB0l7OfQed1-Hcs8nvaH_/view?usp=sharing).
* Uniform sample of 100,000 pairs (per dataset) of roles in 95TVA&2DVA: [Available here](https://drive.google.com/file/d/1HXmTiM5mEvglLmwaIlUYpt7ZjyJd4GtD/view?usp=sharing)
* Manually Annotated Gold Standard: [Available here](https://drive.google.com/file/d/1JkCXNdwpfyIjdx0odmgJtkjcmZYNjxbX/view?usp=sharing)
* Additionally annotated candidates below 95TVA: [Available here](https://drive.google.com/file/d/1hGYpBeJrgzoOQaLT9JjCIROeV_sTQZBS/view?usp=sharing)
