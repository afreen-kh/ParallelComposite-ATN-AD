# Model Architecture

The proposed framework adopts a parallel and multi-composite learning design to address the heterogeneity of clinical, biomarker, and medication-related data in Alzheimer’s disease diagnosis.

Multiple machine learning models are trained in parallel on distinct feature subsets, allowing each component to specialize in capturing patterns relevant to its respective data modality. The outputs of these parallel learners are subsequently integrated through a meta-model based on majority voting, forming a composite decision mechanism.

This design improves diagnostic robustness by leveraging complementary information sources and reducing reliance on any single predictive component. The architecture is particularly suited for multi-class diagnostic settings involving overlapping disease stages.
