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

The repository contains the following main files:

#### KNN Imputation

- `Predicting The Pitch using KNN imputation.ipynb` – Jupyter Notebook containing the KNN-based missing-data imputation and modelling workflow.
- `Predicting The Pitch using KNN imputation.html` – HTML version of the KNN notebook for convenient inspection.
- `Predicting The Pitch using KNN imputation.pdf` – PDF version of the KNN notebook.

#### Median Imputation

- `Predicting The Pitch using Median Imputation.ipynb` – Jupyter Notebook containing the median missing-data imputation and modelling workflow.
- `Predicting The Pitch using Median Imputation.html` – HTML version of the median-imputation notebook for convenient inspection.
- `Predicting The Pitch using Median Imputation.pdf` – PDF version of the median-imputation notebook.

#### Datasets

- `train_home_team_statistics_df.csv` – training data containing home-team statistics.
- `train_away_team_statistics_df.csv` – training data containing away-team statistics.
- `test_home_team_statistics_df.csv` – testing data containing home-team statistics.
- `test_away_team_statistics_df.csv` – testing data containing away-team statistics.
- `Y_train_1rknArQ.csv` – training target data.
- `Y_train_supp.csv` – supplementary training target data.
- `Y_test_random_sEE2QeA.csv` – testing target data.

The original player-level training and testing datasets are substantially larger than the other project files and are addressed separately in the data availability section below.

### Data

The project uses team-level and player-level football data. The datasets contain historical team and player information used to construct the match-level modelling dataset.

The following team-level training and testing datasets and target files are included in this repository:

- Home-team training data
- Away-team training data
- Home-team testing data
- Away-team testing data
- Training and testing target data

The player-level training and testing datasets are substantially larger than the other project files and are therefore not included in the repository at present because of their file size.

These player-level datasets were used in the original analysis and are required to reproduce the complete preprocessing, aggregation, missing-data imputation and modelling workflow described in the dissertation.

The notebooks document the processing steps applied to the player-level data, including aggregation of player-level observations to the match level.

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
