# scRNAseq-atopic-dermatitis-ILCs

Reanalysis of scRNA-seq data from Alkon et al. (2021) on innate lymphoid cells in atopic dermatitis using **Seurat**, **DoubletFinder**, **Harmony**, **CellChat**, and **SingleR**.

## 📚 Project Overview

This repository contains a single-cell RNA sequencing (scRNA-seq) analysis pipeline based on the study:

> **Alkon N, Bauer WM, Krausgruber T, et al.**  
> *Single-cell analysis reveals innate lymphoid cell lineage infidelity in atopic dermatitis.*  
> *Journal of Allergy and Clinical Immunology.* 2021;148(2):474–488.e11.  
> [https://doi.org/10.1016/j.jaci.2021.07.025](https://doi.org/10.1016/j.jaci.2021.07.025)

The dataset focuses on **innate lymphoid cells (ILCs)** in lesional and non-lesional skin from patients with **atopic dermatitis**, revealing lineage infidelity and immune dysregulation.

## 🧰 Tools Used

This analysis uses the following R-based tools:
- **Seurat** – Preprocessing, clustering, and visualization
- **DoubletFinder** – Doublet detection and removal
- **Harmony** – Batch correction and integration
- **SingleR** – Automated cell type annotation
- **CellChat** – Intercellular communication analysis

## 🔗 Data Access

**Note:** This project presents a reanalysis of publicly available scRNA-seq data. **Raw data files are not included** in this repository.  
The dataset can be accessed via its **GEO accession number**, which is provided in the relevant analysis script.

---
