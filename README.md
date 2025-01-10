# Heart Disease Dataset Analysis using PCA

This repository demonstrates the application of **Principal Component Analysis (PCA)** on the Heart Disease dataset to reduce dimensionality and visualize the dataset effectively. The PCA implementation helps explore the relationships between features while retaining the maximum possible variance in a lower-dimensional space.

## Features of the Repository

- **Dataset**: The heart disease dataset includes various clinical features such as age, blood pressure, cholesterol levels, and more. These features are analyzed to predict the presence or absence of heart disease.
- **Preprocessing**:
  - Data cleaning and handling of missing values.
  - Normalization or standardization to prepare data for PCA.
- **PCA Implementation**:
  - Dimensionality reduction to extract the most relevant components.
  - Exploration of explained variance ratio to determine the optimal number of components.
- **Visualization**:
  - bar plots for better understanding.
  - box plot to identify the outliers
- **Machine Learning Integration**:
  - Comparison of model performance with and without PCA for tasks like classification.

## Goals

1. To reduce the dimensionality of the dataset while retaining key information.
2. To improve computational efficiency for downstream machine learning tasks.
3. To visualize relationships between features in reduced dimensions.

## Prerequisites

- Python 3.x
- Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/heart-disease-pca.git
   ```
2. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the analysis script:
   ```bash
   python pca_analysis.py
   ```

## Results

- **Explained Variance**: Analysis of how much variance each principal component captures.
- **Reduced Dimensionality**: Visualization of the dataset in 2D and 3D spaces.
- **Model Insights**: Comparative performance analysis of models pre- and post-PCA.

## Conclusion

PCA is a powerful technique for reducing the dimensionality of datasets like the Heart Disease dataset. This project provides insights into the significance of each feature and offers a streamlined workflow for integrating PCA into machine learning pipelines.
