# PDAC miRNA clinical project
This repository demonstrates an independent analysis of miRNA differential expression in Pancreatic Ductal Adenocarcinoma (PDAC), using publicly available datasets.
#DATA1
- **Source** : Gene Expression Omnibus (GEO), accession  **GSE226762** .
- Raw miRNA count matrices and Patient information data are available under `data1/`.
# Workflow
->  Preprocessed data and normalization . (`processed/results`)
-> Differential expression analysis and visualization via R . (`scripts/mirna_analysis.R`). (`results/`)
-> Output: DE miRNA table : (`results/DE-miRs from PDAC Patient Tissue.csv/`) and volcano plot :( `results/DE-miRs of PDAC patient.jpeg` )
