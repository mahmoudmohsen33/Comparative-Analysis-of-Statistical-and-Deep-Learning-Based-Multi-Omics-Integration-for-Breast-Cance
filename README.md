#  Comparative Analysis of Statistical and Deep Learning-Based Multi-Omics Integration for Breast Cancer Subtype Classification

This repository supports our study comparing two approaches for multi-omics integration—MOFA+ (statistical) and MoGCN (deep learning)—applied to breast cancer subtype classification. The project leverages transcriptomics, epigenomics, and microbiome data from 960 breast cancer patients to evaluate how each integration method contributes to molecular subtyping and pathway discovery.

---

##  Graphical Abstract

![Methodology](https://github.com/user-attachments/assets/a534ed27-4855-40df-9425-6a6b57b1956b)

---

##  Abstract (Paraphrased)

Breast cancer remains one of the leading causes of cancer mortality worldwide. The disease's subtype heterogeneity complicates early detection, clinical management, and therapeutic targeting. Integrating multiple omics layers has emerged as a promising strategy to improve breast cancer subtype prediction. However, a comparative evaluation of different integration strategies is still limited.

In this study, we analyzed multi-omics data from 960 breast cancer patients, incorporating transcriptomics, microbiome, and epigenomics profiles. We compared two integration methods—MOFA+ (a statistical model) and MoGCN (a graph-based deep learning model)—across two key evaluation aspects. First, we measured the discriminative power of features selected by each method using both linear and nonlinear classification models. Second, we examined the biological relevance of these features in relation to known breast cancer pathways.

Our results show that MOFA+ outperformed MoGCN in both classification accuracy and pathway enrichment. Specifically, MOFA+ achieved a higher F1 score (0.75) in nonlinear classification and identified more biologically meaningful pathways, including Fc gamma R-mediated phagocytosis and the SNARE signaling pathway. These findings highlight the effectiveness of MOFA+ in unsupervised multi-omics feature selection and underscore the broader potential of integrative approaches to improve personalized breast cancer treatment.

---

##  Repository Structure

```bash
MOFA/         - MOFA+ training and feature extraction scripts (R)
MoGCN/        - MoGCN autoencoder training and latent feature extraction (Python)
Machine learining/    - Jupyter notebooks for ML analysis and visualization (classification, clustering)
README.md     - This file
