# Neural Decoding Methods

A simulation-based computational neuroscience project exploring how stimulus information can be recovered from neural population activity. The study compares Bayesian, maximum-likelihood, logistic-regression, and population-vector decoders under different population sizes, noise-correlation levels, and tuning widths. It also uses mutual information to measure how closely each decoder approaches the theoretical information limit.

## Highlights

- Simulated stimulus-dependent spike counts using Poisson neural response models
- Compared four decoding strategies on the same population data
- Studied the effects of correlated noise and population size
- Extended the analysis to directionally tuned neural populations
- Measured decoded information in bits

## Results

- Bayesian and maximum-likelihood decoding reached **83.8% accuracy** in the initial four-stimulus experiment
- With 50 neurons, Bayesian decoding reached **99.7% accuracy** and recovered **1.962 of the theoretical 2 bits**
- On the eight-direction task, Bayesian and maximum-likelihood decoding reached **90.8% accuracy**
- Population-vector decoding was competitive but more sensitive to tuning width

## Tech Stack

`Python` · `NumPy` · `SciPy` · `scikit-learn` · `Matplotlib`

## Notebook

[View the notebook](./neural-decoding-comparison.ipynb)

[Open in Google Colab](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPOSITORY/blob/main/neural-decoding/neural-decoding-comparison.ipynb)
