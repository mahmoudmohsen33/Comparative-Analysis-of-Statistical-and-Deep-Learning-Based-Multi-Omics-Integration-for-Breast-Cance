# Test Data for Multi-Omics Integration

This folder contains sample test data and metadata used to validate and demonstrate the multi-omics integration and machine learning evaluation pipelines.

##  Contents

- **Omics Data Files:**
  - Small-scale datasets representing three omics types (transcriptomics, epigenomics, microbiomics).
  - Each dataset contains **4 samples** used for testing and demonstration purposes.

- **Metadata File:**
  - A clinical metadata file providing detailed annotations for each sample.

##  Omics Data Details

Each omics file provides quantitative measurements (expression levels, methylation rates, microbial abundance) across a small set of features for 4 samples.

**Intended Use:**
- Testing preprocessing scripts
- Debugging feature selection and model evaluation pipelines
- Demonstrating multi-omics integration workflows (e.g., MOFA, MoGCN)

##  Metadata File Details

The metadata file includes rich clinical and pathological annotations, such as:

- **Cancer and Disease Information:**
  - Neoplasm Disease Stage (AJCC Code)
  - Cancer Type
  - Detailed Cancer Subtypes
  - Tumor Histologic Grade
  - Tumor Anatomic Site
  - Tumor Type

- **Genetic and Molecular Features:**
  - Aneuploidy Score
  - Fraction Genome Altered
  - Mutation Count
  - MSI Scores (MSI.MANTIS, MSIsensor)
  - Tumor Mutation Burden (TMB nonsynonymous)

- **Clinical Outcomes:**
  - Overall Survival (Months and Status)
  - Disease-Free Survival (Months and Status)
  - Progression-Free Survival (Months and Status)
  - Disease-Specific Survival

- **Demographic and Sample Information:**
  - Ethnicity and Race Categories
  - Sex
  - Sample Type
  - Tissue Collection Information
  - Patient Weight
  - Form Completion Dates

- **Other Annotations:**
  - ICD-10 Classification Codes
  - Oncotree Codes
  - Hypoxia Scores (Buffa, Ragnum, Winter)
  - Genetic Ancestry Labels
  - Prior Diagnosis Status
  - Radiation Therapy Status
  - Number of Samples per Patient

*(All fields are available for only 4 test samples for demonstration purposes.)*

##  Purpose

- **Test** and **validate** multi-omics analysis pipelines on a small, manageable dataset.
- Ensure the workflows for feature selection, model evaluation, and clinical outcome prediction work correctly.
- Quickly debug integration algorithms without running heavy full datasets.

##  Notes

- This is a **synthetic or reduced real-world dataset** meant **only for testing and demonstration purposes**.
- It does not fully represent biological complexity or clinical study populations.

