# Predicting-the-Pitch

## MSc Dissertation

**Football match outcome prediction using statistical and machine-learning models with median and KNN missing-data imputation.**

### Project Overview

This repository contains the source code, datasets, and supporting files for an MSc dissertation investigating football match outcome prediction using statistical and machine-learning approaches.

The project compares five predictive models:

- Multinomial Logistic Regression
- Decision Tree
- Random Forest
- XGBoost
- Multilayer Perceptron (MLP)

The study also compares two approaches to missing-data imputation:

- Median imputation
- K-Nearest Neighbour (KNN) imputation

The objective is to evaluate how different modelling approaches and missing-data treatments affect the prediction of three football match outcomes: home win, draw, and away win.

### Repository Contents

The repository contains:

- Python/Jupyter notebooks implementing the median and KNN imputation approaches and predictive modelling.
- HTML and PDF versions of the notebooks for code inspection.
- Team-level training and testing datasets.
- Target/outcome datasets.
- Supporting project documentation.

### Data

The project uses team-level and player-level football data.

The player-level training and testing datasets are substantially larger than the other project files and are not currently included in this repository because of their file size.

The notebooks require the original project datasets to reproduce the complete preprocessing, missing-data imputation, and modelling workflow described in the dissertation.

### Software and Methods

The analysis was conducted using Python and commonly used machine-learning and statistical libraries.

The notebooks implement:

1. Data preparation and preprocessing
2. Missing-data analysis
3. Median and KNN imputation
4. Training and testing data preparation
5. Statistical and machine-learning models
6. Model evaluation and comparison

### Reproducing the Analysis

To inspect the implementation, open the Jupyter notebooks included in this repository.

The HTML and PDF versions are also provided for convenient inspection of the implemented workflow and results.

The original project datasets should be placed in the appropriate working directory before running the notebooks. File paths may need to be adjusted depending on the local environment.

### Dissertation

The full methodology, experimental design, results, discussion, limitations, and conclusions are presented in the accompanying MSc dissertation report.
