# PDAC miRNA clinical project
This repository demonstrates an independent analysis of miRNA differential expression in Pancreatic Ductal Adenocarcinoma (PDAC), using publicly available datasets.
---
# Data
- **Source** : Gene Expression Omnibus (GEO), accession  **GSE226762** .
- Raw miRNA count matrices and Patient information data are available under `data1/`.
# Workflow
- Preprocessed data and normalization . (`processed/results`)
- Differential expression analysis and visualization via R . (`scripts/mirna_analysis.R`). (`results/`)
- Output: DE miRNA table : (`results/DE-miRs from PDAC Patient Tissue.csv/`) 
  and volcano plot :( `results/DE-miRs of PDAC patient.jpeg` )
# Objective : To Find  Differential expression analysis of microRNAs (miRNAs) in pancreatic ductal adenocarcinoma (PDAC) using publicly available datasets.
 **Data type** : miRNA expression counts (tissue samples).
  - Process:
    - Selected tissue-specific samples.
    - Cleaned sample IDs to match metadata.
    - Saved processed count matrix in `processed/`.
     
       # **Methods** 
     - ***Data Cleaning***
     - Filtered sample data and matched with metadata
     - Prepared expression count matrix
    - ***Differential Expression Analysis***
     - Performed with DESeq2
     -  Threshold: log2 fold change ±1, adjusted p-value < 0.05
     - ***Visualization***
     - Volcano plot using ggplot2
     - Highlighted significantly up/downregulated miRNAs
          # **Result**
       - DE-miRNA table: `results/DE-miRs from PDAC Patient Tissue.csv/`
       - Volcano plot: `results/DE-miRs of PDAC patient.jpeg`





