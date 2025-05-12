
# Synthetic Data Evaluation

This repository contains a Jupyter Notebook that evaluates the quality and utility of synthetic data compared to real data using statistical, visual, and machine learning techniques.

## 📑 Overview

Synthetic data is increasingly used in data science workflows to protect privacy and enhance data availability. This notebook provides a comprehensive evaluation of synthetic data quality across various dimensions:

- Correlation structure
- Principal Component Analysis (PCA)
- Supervised learning performance
- Wasserstein distance comparison

## 🚀 Getting Started

### Prerequisites

Ensure the following Python libraries are installed:

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- scipy

You can install them with:

```bash
pip install pandas numpy seaborn matplotlib scikit-learn scipy
```

### Usage

1. Clone the repository.
2. Place your real and synthetic datasets in the project directory.
3. Open the Jupyter notebook:
   ```bash
   jupyter notebook Synthetic_Data_Evaluation.ipynb
   ```
4. Run each cell sequentially to compare the datasets.

## 📊 Evaluation Metrics

- **Correlation Heatmaps:** Compare the structure of relationships between variables.
- **PCA Visualization:** Observe overall data distributions.
- **Random Forest Classifier Performance:** Train/test models on real and synthetic data to evaluate utility.
- **Wasserstein Distance:** Quantifies how similar each feature's distribution is between datasets.

## 🔗 Dataset

The real dataset used in this notebook can be found on [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud).

## 📌 Notes

- The notebook assumes both datasets have the same columns and structure.
- Label encoding is used for categorical variables.
- Feature scaling is applied before PCA and classification tasks.

## 🧠 Author

- This notebook was developed for evaluating synthetic data quality in a structured and replicable way.
- Customize the evaluation techniques to suit your dataset's nature and use case.

