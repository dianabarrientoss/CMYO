# Family Exome Analysis Identifies a Rare Recessive PAX7 Variant Underlying Congenital Myopathy

Release date: 01-06-2026

Author: Diana Barrientos

DOI: https://doi.org/10.1012/s00112-006-12012-06

This repository contains the code and analysis used in order to determined the *PAX7* variant of a child affected by congenital miophaty

---

## 📌 Table of Contents
- [Overview](#overview)
- [Repository Structure](#repository-structure)
- [Prerequisites & Environment Setup](#prerequisites--environment-setup)
- [Citation & Contact](#citation--contact)

---

## 📖 Overview

This workflow was designed to analyze Whole Exome Sequencing (WES) data from a family with a child affected by congenital myopathy. The analysis done in Rstudio includes: data import, variant filt[...]

## 📂 Repository Structure


├── CODES/                                                              # Source code for analysis
│   ├── [Variant_filtering.Rmd`](CODES/Variant_filtering.Rmd)           # Includes variant filtering, and trio analysis segregation
│   ├── Variant_filtering.nb.html                                       # HTML file of Variant_filtering.Rmd
│   ├── Candidate_variants.Rmd                                          # Includes candidate variants information from databases
│   ├── Candidate_variants.nb.html                                      # HTML file of Candidate_variants.Rmd
├── IMAGES/                                                             # Pedigree images before and after variant identification
│   ├── Family_pedigree_prior_to_molecular_diagnosis                    # Pedigree given
│   ├── Family_pedigree_annotated_with_PAX7_genotypes                   # Pedigree after *PAX7* variant identification 
└── README.md                                                           # This documentation file


## 💻 Prerequisites & Environment Setup

To ensure reproducibility of the statistical and computational analyses, we recommend using the following software:

```
- Rstudio (version 2026.1.1.403)
- R (version 4.5.3), with the following packages:
  - readxl (version 1.4.5)
```

## ✉️ Citation & Contact
If you use the code, pipelines, or processed data from this repository, please don't forget to cite this work:

Barrientos-González, D., & Gonzaga-Jauregui, C. (2026). Family Exome Analysis Identifies a Rare Recessive PAX7 Variant Underlying Congenital Myopathy. Naturee, https://doi.org/10.1012/s00112-006-[...]

For questions regarding the code or bugs, please contact:
- Diana Barrientos - diana.barrientos.glz@gmail.com

## ❗Note

This work was done as a final project for the Human Genetics and Genomics course from the Bachelor's Degree in Genomic Sciences at UNAM.
