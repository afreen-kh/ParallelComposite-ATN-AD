# Development of a Robust Parallel and Multi-Composite Machine Learning Model for Improved Diagnosis of Alzheimer’s Disease

**Afreen Khan**, S. Zubair, M. Shuaib, A. Sheneamer, S. Alam, and B. Assiri  
*Frontiers in Neuroscience*, 2024

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

## Dataset Scope and Experimental Setup

The experimental evaluation in this study was conducted using clinical and biomarker data obtained from the Alzheimer’s Disease Neuroimaging Initiative (ADNI). The dataset includes subjects spanning cognitively normal (CN), mild cognitive impairment (MCI), and Alzheimer’s disease (AD) diagnostic categories.

The feature space comprises:
- Demographic and clinical assessment variables
- Cognitive test scores
- AT(N) protein biomarkers, including amyloid-beta (Aβ), total tau (Tau), and phosphorylated tau (pTau)
- Dementia-associated drug usage information reflecting real-world clinical treatment patterns

To accommodate the heterogeneous nature of these features, the proposed framework employs parallel learning streams, each optimized for a specific feature group. Outputs from individual learning components are integrated using a multi-composite decision strategy to enhance diagnostic robustness.

The study design follows a supervised learning paradigm with appropriate train–test separation and standard clinical evaluation metrics. All experiments adhere to ADNI data usage policies, and no raw or subject-level data are redistributed through this repository.

---

## Results Summary

The proposed parallel and multi-composite machine learning framework demonstrated strong diagnostic performance across multi-class Alzheimer’s disease classification tasks. The study addressed the challenge of early AD diagnosis by integrating heterogeneous data sources, including neuropsychological assessments, dementia-associated drug usage, and AT(N) cerebrospinal fluid protein biomarkers.

A multinomial classification setting was considered, comprising five diagnostic categories: cognitively normal, significant subjective memory concern, early mild cognitive impairment, late mild cognitive impairment, and Alzheimer’s disease. The hybrid-clinical design employed multiple machine learning models operating in parallel, with final predictions determined through majority voting within a meta-model framework.

Experimental evaluation revealed that incorporating protein biomarkers alongside baseline clinical features significantly improved diagnostic accuracy. The highest performance was achieved when baseline features were combined with protein biomarkers, yielding a maximum classification accuracy of **97.60%**. The meta-model also exhibited consistent performance when trained using individual protein biomarkers, as well as when all AT(N) biomarkers were jointly included.

Analysis of dementia-associated drug usage further indicated that the model functioned effectively both when all drug categories were incorporated and when individual drug variables were evaluated independently. These findings suggest that medication-related information provides complementary diagnostic value when integrated with clinical and biomarker data.

Overall, the results confirm that parallel feature learning and composite decision aggregation enhance robustness in multi-class Alzheimer’s disease diagnosis. The proposed framework offers a flexible and extensible design capable of accommodating diverse clinical and biological inputs, supporting its potential applicability in early-stage diagnostic modeling and future neurodegenerative disease research.


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
  author={Khan, Afreen and Zubair, Swaleha and Shuaib, Mohammed and Sheneamer, Abdullah and Alam, Shadab and Assiri, Basem},
  journal={Frontiers in Neuroscience},
  year={2024},
  doi={10.3389/fnins.2024.1391465}
}
