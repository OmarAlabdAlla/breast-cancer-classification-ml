# Breast Cancer Classification (ML)

Machine learning-based classification of breast tumors (malignant vs benign) using the Wisconsin Diagnostic Breast Cancer dataset.

## Problem

Early detection of breast cancer is critical. This project builds models to classify tumors based on cell nucleus features extracted from medical data.

## Dataset

* Wisconsin Diagnostic Breast Cancer (WDBC)
* 569 samples (357 benign, 212 malignant)
* 30 numerical features per sample
* Source: UCI Machine Learning Repository

## Approach

* Data preprocessing and feature analysis
* Implementation of multiple models:

  * Rule-based classifiers
  * Random Forest
  * Hybrid approach (Decision Tree + Logistic Regression)
* Model evaluation using cross-validation and classification metrics

## Results

The models are evaluated using accuracy, precision, recall, and confusion matrix.

* Best performance achieved using the hybrid model
* Random Forest also shows strong performance
* Rule-based models provide interpretable results with competitive accuracy

(See notebook for detailed results and visualizations)

## How to Run

```bash
jupyter notebook breast_cancer_classification.ipynb
```

## Notes

This is a course project for educational purposes only.
