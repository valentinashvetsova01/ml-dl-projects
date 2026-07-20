# Ad Click Prediction with MLP and LIME

A deep learning classification project that predicts whether a user will click an online advertisement from behavioral, demographic, geographic, and temporal information. The project combines an MLP classifier with a structured preprocessing pipeline and LIME explanations that translate individual predictions into human-readable feature contributions.

## Highlights

- Processed numerical, categorical, timestamp, and high-dimensional search-query features
- Evaluated model configurations with stratified cross-validation
- Used a multilayer perceptron with batch normalization, dropout, and AdamW
- Built a compatibility layer between the original preprocessing pipeline and LIME
- Generated local explanations for individual click predictions

## Results

The selected two-block MLP achieved:

- **Cross-validation F1: 0.947**
- **Cross-validation accuracy: 0.947**
- **Test F1: 0.963**
- **Test accuracy: 0.963**

The final confusion matrix contained only two false positives and five false negatives.

## Tech Stack

`Python` · `TensorFlow` · `Keras` · `SciKeras` · `pandas` · `scikit-learn` · `LIME` · `Matplotlib` · `Seaborn`

## Notebook

[View the notebook](./ad-click-prediction-lime.ipynb)

[Open in Google Colab](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPOSITORY/blob/main/ad-click-prediction/ad-click-prediction-lime.ipynb)
