# Supervised Learning

This repository will hold the supervised learning content that I teach at Europeia University on a course about Big Data and Data Analytics. Program can be found [here](https://www.europeia.pt/pos-graduacao-data-analytics-big-data-online/) - in portuguese though.

The notebooks on this repository are separated into theory and practice.

### Theory

1. Data Collection
   * 1.1\. Data Sources
   * 1.2\. Data Collection Considerations
2. Data Exploration and Preparation
   * 2.1\. Data Exploration
   * 2.2\. Data Preparation/Cleaning
3. Split Data into Training and Test Sets
   * 3.1\. Holdout Method
   * 3.2\. Cross Validation
   * 3.3\. Data Leakage
   * 3.4\. Best Practices
4. Choose a Supervised Learning Algorithm
   * 4.1\. Consider algorithm categories
   * 4.2\. Evaluate algorithm characteristics
   * 4.3\. Try multiple algorithms
5. Train the Model
   * 5.1\. Objective Function (Loss/Cost Function)
   * 5.2\. Optimization Algorithms
   * 5.3\. Overfitting and Underfitting
6. Evaluate Model Performance
   * 6.1\. Performance Metrics for Regression Models
   * 6.2\. Performance Metrics for Classification Models
7. Model Tuning and Selection
   * 7.1\. Hyperparameter Tuning
   * 7.2\. Ensemble Methods

### Practice

- [Regression Example](https://colab.research.google.com/github/DidierRLopes/supervised-learning/blob/main/example-regression.ipynb)

- Classification examples:

  - [kNN](https://colab.research.google.com/github/DidierRLopes/supervised-learning/blob/main/example-classification-iris-kNN.ipynb)
  - [Random Forest](https://colab.research.google.com/github/DidierRLopes/supervised-learning/blob/main/example-classification-cancer-random-forest.ipynb)
  - [SVM](https://colab.research.google.com/github/DidierRLopes/supervised-learning/blob/main/example-classification-wine-SVM.ipynb) 

## Get Started

Ensure that you have install conda.

1. Create a new environment

```python
conda create -n ml
```

2. Activate the new environment

```python
conda activate ml
```

3. Install poetry with conda

```python
conda install poetry
```

4. Install all packages

```python
poetry install
```

## Disclaimer

There's a lot that can be improved, so feel free to send a PR with suggestions.
