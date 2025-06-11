# scRNAseq-atopic-dermatitis-ILCs
Reanalysis of scRNA-seq data from Alkon et al. (2021) on innate lymphoid cells in atopic dermatitis using Seurat, DoubletFinder, Harmony, CellChat, and SingleR. DOI: 10.1016/j.jaci.2021.07.025

This repository contains a single-cell RNA sequencing (scRNA-seq) analysis pipeline based on the study:

Alkon N, Bauer WM, Krausgruber T, et al.
Single-cell analysis reveals innate lymphoid cell lineage infidelity in atopic dermatitis.
J Allergy Clin Immunol. 2021;148(2):474-488.e11. doi: 10.1016/j.jaci.2021.07.025

In this project, we use R-based tools including:

Seurat for preprocessing, clustering, and visualization

DoubletFinder to identify and remove doublets

Harmony for batch correction

SingleR for automated cell type annotation

CellChat to explore cell-cell communication

The dataset focuses on innate lymphoid cells (ILCs) in skin from patients with atopic dermatitis, revealing lineage plasticity and immune dysregulation.

This repository provides:

A reproducible workflow in RMarkdown

Rendered HTML reports of the analysis

Scripts organized by preprocessing, integration, annotation, and signaling analysis

Note: This is a reanalysis of publicly available data and does not include raw data files. The dataset can be accessed via its GEO accession number, which is provided in the corresponding analysis script.
