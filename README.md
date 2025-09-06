# Reproducing and Extending "A Novel Approach for Predicting Anthropogenic CO2 Emissions Using Machine Learning Based on Clustering"

## Overview
This project consists of two Jupyter notebooks:
1. **Reproduction Notebook**: Reproduces the methodology of the original paper using OWID data, clustering, and PCA (instead of boosting).  
2. **Extension Notebook**: Extends the study with additional clustering models, PCA vs non-PCA comparison, anomaly detection, temporal analysis, and policy insights.  

## Original Paper
- Title: *A Novel Approach for Predicting Anthropogenic CO2 Emissions Using Machine Learning Based on Clustering of the CO2 Concentration*  
- Journal: Atmosphere, 2024  
- Authors: [Provide citation here]

## Differences from Original Paper
- **Dataset**: OWID global dataset instead of China-specific ODIAC.  
- **Algorithms**: KMeans, Hierarchical, and GMM instead of boosting (CatBoost, LightGBM, XGBoost).  
- **Focus**: Transparency, reproducibility, and interpretability.  
- **Additional Analyses**: PCA comparison, anomaly detection, temporal evolution, and policy insights.  

## Skills Demonstrated
- Data cleaning & preprocessing (Python, Pandas, NumPy)  
- Dimensionality reduction (PCA)  
- Unsupervised learning (KMeans, Hierarchical, GMM)  
- Model evaluation (inertia, silhouette score)  
- Anomaly detection (Isolation Forest)  
- Temporal trend analysis & visualization (Seaborn, Matplotlib)  
- Policy analysis and interpretation  

## Project Structure
- reproduction_notebook.ipynb # Step-by-step replication of the paper
- extension_notebook.ipynb # Extended analysis and new experiments

## Key Findings
- PCA aids interpretability, but clustering performance is similar in high dimensions.
- K-Means provides the most stable clusters; GMM captures uncertainty; Hierarchical adds structural insights.
- Anomalies reveal global shocks (COVID-19, energy crises).
- Temporal analysis shows transitions of countries towards renewable dependence.

## Applications
- Climate research
- Environmental policy planning
- AI/ML for sustainability

## License
Released under MIT License
