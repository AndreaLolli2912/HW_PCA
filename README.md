# PCA Homework (HW PCA)

This repository hosts all the materials and code for the mandatory project on Principal Components Aanalysis, for the course *Computational Linear Algebra for Large Scale Problems* (A.Y. 2024/2025). It features Principal Component Analysis through scikit-learn module to reduce a 150-feature survey dataset to at most 5 components (preserving at least 33% variance) and k-Means clustering to identify the profiles described by the coefficients of the 5 PCs.

---

## Contents

- **`HW_PCA.pdf`**: Original homework instructions.
- **`HWpca_Lolli.ipynb`**: My Jupyter Notebook with code and analysis.
- **Data**: Survey dataset files (`responses_hw.csv` and `columns_hw.csv`).

---

## Task Overview

1. **Dimensionality Reduction**  
   - Use PCA to reduce the dataset to at most 5 principal components while retaining at least 33% of the total variance.

2. **Clustering**  
   - Apply k-Means clustering on the PCA-transformed data to identify 3–10 distinct customer profiles.

3. **Analysis & Interpretation**  
   - Analyze the principal components and interpret the clusters in the context of the survey data.

---

## Libraries & Tools

- **NumPy / Pandas**: For data manipulation and numerical operations.
- **scikit-learn**: For PCA and k-Means clustering.
- **Matplotlib / Seaborn**: For visualizations.

---

## Getting Started

1. **Install Requirements**: Refer to [`requirements.txt`](requirements.txt).
2. **Run Notebook**: Open and execute `HWpca_Lolli.ipynb` using Jupyter Notebook.
3. **Explore**: Adjust PCA and clustering parameters to further experiment with the analysis.

---

## Contributions & Contact

This project is shared for academic purposes. For questions or suggestions, please open an issue or contact me directly.
