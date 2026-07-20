# Stroke Risk Prediction

A machine learning project focused on identifying patients with an elevated risk of stroke from clinical and demographic data. The workflow addresses missing values, categorical variables, severe class imbalance, feature selection, and model comparison through nested cross-validation. The final model combines oversampling, statistical feature selection, and a regularized linear classifier.

## Highlights

- Analyzed **5,110 patient records**
- Built reusable preprocessing for numerical and categorical features
- Handled missing BMI and smoking-status values
- Compared linear, tree-based, boosting, and support-vector models
- Used nested cross-validation to reduce model-selection bias
- Evaluated performance primarily with ROC AUC because of class imbalance

## Results

The selected pipeline used:

- `RandomOverSampler`
- `SelectKBest`
- `RidgeClassifier`

It achieved:

- **Cross-validation ROC AUC: 0.843**
- **Test ROC AUC: 0.838**

The analysis also showed that more complex models did not meaningfully outperform a well-regularized linear baseline, suggesting that the available features impose a practical performance ceiling.

## Tech Stack

`Python` · `pandas` · `scikit-learn` · `imbalanced-learn` · `XGBoost` · `LightGBM` · `Matplotlib` · `Seaborn`

## Notebook

[View the notebook](./stroke-risk-prediction.ipynb)

[Open in Google Colab](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPOSITORY/blob/main/stroke-risk-prediction/stroke-risk-prediction.ipynb)

> This project is an educational analysis and is not intended for clinical diagnosis.
