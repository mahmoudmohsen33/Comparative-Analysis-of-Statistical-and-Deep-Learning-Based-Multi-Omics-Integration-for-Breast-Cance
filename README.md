#  Comparative Analysis of Statistical and Deep Learning-Based Multi-Omics Integration for Breast Cancer Subtype Classification

This repository supports our study comparing two approaches for multi-omics integration—MOFA+ (statistical) and MoGCN (deep learning)—applied to breast cancer subtype classification. The project leverages transcriptomics, epigenomics, and microbiome data from 960 breast cancer patients to evaluate how each integration method contributes to molecular subtyping and pathway discovery.

---

##  Graphical Abstract

![Methodology](https://github.com/user-attachments/assets/a534ed27-4855-40df-9425-6a6b57b1956b)

---

##  Abstract

Breast cancer remains one of the leading causes of cancer mortality worldwide. The disease's subtype heterogeneity complicates early detection, clinical management, and therapeutic targeting. Integrating multiple omics layers has emerged as a promising strategy to improve breast cancer subtype prediction. However, a comparative evaluation of different integration strategies is still limited.

In this study, we analyzed multi-omics data from 960 breast cancer patients, incorporating transcriptomics, microbiome, and epigenomics profiles. We compared two integration methods—MOFA+ (a statistical model) and MoGCN (a graph-based deep learning model)—across two key evaluation aspects. First, we measured the discriminative power of features selected by each method using both linear and nonlinear classification models. Second, we examined the biological relevance of these features in relation to known breast cancer pathways.

Our results show that MOFA+ outperformed MoGCN in both classification accuracy and pathway enrichment. Specifically, MOFA+ achieved a higher F1 score (0.75) in nonlinear classification and identified more biologically meaningful pathways, including Fc gamma R-mediated phagocytosis and the SNARE signaling pathway. These findings highlight the effectiveness of MOFA+ in unsupervised multi-omics feature selection and underscore the broader potential of integrative approaches to improve personalized breast cancer treatment.

---
## 📄 Publication

Our paper was published in *Journal of Translational Medicine* (2025):  
**Comparative Analysis of Statistical and Deep Learning-Based Multi-Omics Integration for Breast Cancer Subtype Classification**  
[🔗 View the full paper](https://link.springer.com/article/10.1186/s12967-025-06662-5)  

---
##  Repository Structure

```bash
MOFA_Code/                           - MOFA+ training and feature extraction scripts (R)
MoGCN/                           - MoGCN autoencoder training and latent feature extraction (Python)
Feature_Evaluation_MOFA_MoGCN/    - Jupyter notebooks for machine learning evaluation and visualization (classification, clustering) based on selected features
Test_Data/                       - Small-scale multi-omics datasets and metadata for pipeline testing
plot.R                            - R script for generating analysis plots and visualizations
README.md                        - Repository overview and instructions

