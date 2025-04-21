# MoGCN Module
This folder contains the deep learning-based autoencoder used to generate latent features from multi-omics data for breast cancer subtype analysis.
## Overview
We used the `AE_run.py` script from the MoGCN pipeline (available at [Lifoof/MoGCN](https://github.com/Lifoof/MoGCN)) to perform autoencoder-based dimensionality reduction across three omics layers: transcriptomics, epigenomics, and microbiome.
This model was used to generate a latent feature matrix (`latent_data.csv`), which was used in our downstream subtype classification and clustering analysis.
## Input Files
We used the following preprocessed and scaled multi-omics datasets:
- `scaled_transcriptome.csv` – Transcriptomics (e.g., RNA-seq FPKM)
- `scaled_Methylation.csv` – DNA methylation
- `scaled_Microbiome.csv` – Microbiome profiles

All files must be in CSV format with matching samples in rows and features in columns.
---
## Command Used
We executed the autoencoder with the following command:
```bash
python AE_run.py -p1 data/scaled_transcriptome.csv -p2 data/scaled_Methylation.csv -p3 data/scaled_Microbiome.csv -m 0 -s 0 -d cpu
