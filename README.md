# Development of a Robust Parallel and Multi-Composite Machine Learning Model for Improved Diagnosis of Alzheimer’s Disease

**Afreen Khan**, S. Zubair, I. Ali  
*Frontiers in Neuroscience, 2024*

🔗 **Paper (PDF):** https://www.frontiersin.org/journals/neuroscience/articles/10.3389/fnins.2024.1391465/full 

---

## Abstract

This study proposes a robust parallel and multi-composite machine learning framework for improving the diagnosis of Alzheimer’s disease by integrating heterogeneous clinical features with AT(N) protein biomarkers and dementia-associated drug usage information. The model is designed to capture complementary diagnostic patterns through parallel learning streams and composite decision aggregation, enabling improved diagnostic accuracy and robustness across clinical cohorts.

---

## Research Contribution

The key methodological contributions of this work include:

- A **parallel learning architecture** designed to handle heterogeneous clinical, biomarker, and medication-related feature spaces
- A **multi-composite modeling strategy** that aggregates multiple predictive components to enhance robustness
- Integration of the **AT(N) biomarker framework** with dementia-associated drug usage for enriched diagnostic modeling
- Systematic evaluation of model performance in the context of Alzheimer’s disease diagnosis

---

## Repository Scope and Purpose

This repository serves as a **research companion** to the published article.

It provides documentation of the **conceptual model architecture, feature grouping strategy, and experimental design** underlying the proposed parallel and multi-composite machine learning framework.

> **Note:**  
> The original implementation was developed as part of the experimental study using restricted clinical datasets and is **not publicly released** due to data governance, privacy, and institutional constraints.

Accordingly, this repository does **not** aim to provide a full reproducibility package or executable training pipeline.

---

## Methodology Overview

The proposed framework is based on:

- Parallel model branches trained on distinct feature groups (clinical variables, AT(N) biomarkers, and drug usage data)
- Composite decision fusion to integrate outputs from multiple predictive components
- Robust evaluation using standard clinical diagnostic metrics

A high-level representation of the framework is shown below.

<p align="center">
  <img src="figures/architecture.png" width="800"/>
</p>

---

## Dataset Description

The study utilizes clinical and biomarker data derived from the Alzheimer’s Disease Neuroimaging Initiative (ADNI), including:

- Demographic and cognitive assessment variables
- AT(N) protein biomarkers (Aβ, Tau, pTau)
- Dementia-associated drug usage information

All data usage complies with ADNI data access and ethical guidelines. No raw data are distributed through this repository.

---

## Intended Use

This repository is intended for:

- Researchers seeking a **conceptual reference** for parallel and composite machine learning designs in clinical diagnostics
- Readers of the associated publication interested in understanding the **architectural and methodological structure** of the proposed model
- Academic use in the context of neurodegenerative disease research

The methodological framework may be extended or re-implemented for related multimodal diagnostic tasks.

---

## Citation

If you use or reference this work, please cite:

```bibtex
@article{khan2024parallel,
  title={Development of a Robust Parallel and Multi-Composite Machine Learning Model for Improved Diagnosis of Alzheimer’s Disease: Correlation with Dementia-Associated Drug Usage and AT(N) Protein Biomarkers},
  author={Khan, Afreen and Zubair, S. and Ali, I.},
  journal={Frontiers in Neuroscience},
  year={2024}
}
