# Wine Quality Classification

## Repository Overview
This repository contains a comparative analysis of machine learning classification techniques for predicting wine quality. The study explores various algorithms, evaluates their performance, and provides insights for improving classification accuracy in real-world applications.

## Objective
The goal of this research is to evaluate and compare multiple machine learning classification models to determine their effectiveness in predicting wine quality. The findings can be applied to similar classification tasks, including assessments for local coconut wine, "Tuba."

## Dataset
The dataset used in this study consists of **1,250 wine samples** with **11 chemical properties** and a **quality label**. The features include:
- **Fixed Acidity**
- **Volatile Acidity**
- **Citric Acid**
- **Residual Sugar**
- **Chlorides**
- **Free Sulfur Dioxide**
- **Total Sulfur Dioxide**
- **Density**
- **pH**
- **Sulphates**
- **Alcohol**
- **Quality (Label: Bad, Fair, Good, Very Good)**

## Machine Learning Models Used
The following algorithms were implemented and evaluated using Weka:
- **Decision Tree (J48)**
- **Naïve Bayes**
- **Random Forest**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**

## Performance Metrics
Each model was assessed using multiple performance metrics:

| Model            | Accuracy | TP Rate | FP Rate | Precision | Recall | F1-Score | MAE   | RMSE  |
|-----------------|----------|---------|---------|-----------|--------|----------|-------|-------|
| Decision Tree   | 82.40%   | 0.824   | 0.040   | 0.842     | 0.824  | 0.829    | 0.0792 | 0.2517 |
| Naïve Bayes    | 89.33%   | 0.893   | 0.027   | 0.900     | 0.893  | 0.895    | 0.0554 | 0.1743 |
| Random Forest  | 87.20%   | 0.872   | 0.032   | 0.879     | 0.872  | 0.874    | 0.0973 | 0.1993 |
| SVM            | 89.07%   | 0.891   | 0.026   | 0.897     | 0.891  | 0.892    | 0.2444 | 0.3231 |
| KNN            | 75.73%   | 0.757   | 0.063   | 0.782     | 0.757  | 0.764    | 0.0983 | 0.3107 |

## Key Findings
- **Naïve Bayes achieved the highest accuracy (89.33%)**.
- **SVM had the best balance between precision and recall**.
- **Decision Trees performed well but struggled with certain classifications**.
- **Random Forest showed strong reliability and robustness against noisy data**.
- **KNN had the lowest accuracy but remained interpretable and simple to implement**.

## Implementation Steps
1. **Data Preprocessing:** Feature selection, normalization, and dataset structuring.
2. **Model Training & Evaluation:** Training different ML models using Weka.
3. **Performance Comparison:** Analyzing classification metrics and confusion matrices.
4. **Result Interpretation:** Identifying the most effective model based on predictive accuracy.

## Conclusion
The study demonstrates that machine learning techniques can effectively classify wine quality. **Naïve Bayes and SVM performed best**, but further improvements can be achieved by fine-tuning hyperparameters and using real-world datasets.

## Future Work
- Experimenting with **deep learning** models for enhanced accuracy.
- Applying models to **real-world datasets** instead of synthetic ones.
- Testing additional preprocessing techniques to optimize feature selection.

## How to Use This Repository
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/Wine-Quality-Classification.git
   ```
2. Load the dataset and preprocess it.
3. Train models using **Weka** or an alternative ML framework.
4. Compare performance using classification metrics.

## Authors
- **Marcelo Rc. D Guevarra**
- **Harley Gotardo**
- **Additional Contributors**

## References
- [Wine Quality Dataset - Kaggle](https://www.kaggle.com/datasets/yasserh/wine-quality-dataset)
- Research papers on machine learning and wine classification.

---
