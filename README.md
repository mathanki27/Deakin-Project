# Protein Signatures as Biomarkers for Cardiovascular Disease Risk in People Living with HIV

## Overview

This repository contains the code and analysis workflow used for a Master's research project investigating plasma protein signatures associated with future cardiovascular events in people living with HIV (PLHIV).

The study used Tandem Mass Tag (TMT)-based quantitative proteomics to compare HIV-positive individuals who subsequently experienced a cardiovascular event with matched HIV-positive controls who remained event-free despite having a similar atherosclerotic burden.

## Research Question

Can specific protein expression signatures identified through proteomic analysis serve as reliable biomarkers for predicting cardiovascular disease risk in HIV-positive patients?

## Methods

The analytical workflow included:

- TMT-based quantitative proteomics
- Protein identification and quantification using FragPipe
- Quality control and data filtering
- Missing value imputation
- Quantile normalisation
- Batch effect correction
- Principal Component Analysis (PCA)
- Differential expression analysis using limma
- Reactome pathway enrichment analysis using mitch

## Repository Contents

| File | Description |
|--------|-------------|
| analysis.Rmd | Main R Markdown analysis workflow |
| analysis.html | Rendered report |
| metadata.csv | Sample metadata |
| mitch.html | Reactome pathway enrichment results |


## Key Findings

- No proteins met the predefined significance threshold after multiple testing correction.
- Pathway-level analysis identified biologically relevant trends involving:
  - Innate immune activation
  - Complement signalling
  - Platelet and extracellular matrix biology
  - Lipid metabolism
  - Mitochondrial function

These findings suggest that cardiovascular risk in PLHIV may be reflected more strongly through coordinated pathway-level changes than through large alterations in individual proteins.

## Author

Mathanki Mehra  
Master of Biotechnology  
Deakin University

## Supervisor

Dr Mark Ziemann  
Burnet Institute

## Disclaimer

Data are not publicly distributed due to participant confidentiality and ethical restrictions.
