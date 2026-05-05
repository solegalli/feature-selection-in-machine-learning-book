[![License https://github.com/solegalli/feature-selection-in-machine-learning/blob/main/LICENSE](https://img.shields.io/badge/license-BSD-success.svg)](https://github.com/solegalli/feature-selection-in-machine-learning/blob/main/LICENSE)
[![Sponsorship https://www.trainindata.com/](https://img.shields.io/badge/Powered%20By-TrainInData-orange.svg)](https://www.trainindata.com/)

## Feature Selection in Machine Learning Book - Code Repository

- Published: August, 2022
- Updated: May, 2026

[<img src="./FSML-bookcover.png" width="248">](https://www.trainindata.com/p/feature-selection-in-machine-learning-book)

## Links

- [Book](https://www.trainindata.com/p/feature-selection-in-machine-learning-book)


## Table of Contents

1. **Basic Selection Methods**
	1. Removing Constant Features
	2. Removing Quasi-Constant Features
	3. Removing Duplicated Features

2. **Correlation Feature Selection**
	1. Removing Correlated Features 
	2. Smart Correlation

3. **Statistical methods**
	1. Chi-square distribution
	2. Anova
	3. Correlation
	4. Mutual information

4. **Univariate Methods**
	1. Single feature classifiers / regressors
	2. Target mean encoding

5. **Wrapper Methods**
	1. Exhaustive Feature Selection
	2. Step Forward Feature Selection
	3. Step Backward Feature Selection 

6. **Embedded Methods: Linear Model Coefficients**
	1. Lasso
	2. Decision tree feature importance

7. **Recursive Feature Elimination**
	1. RFE - embedded importance
	2. RFE - model performance

8. **Alternative Feature Selection Methods**
	1. Feature Shuffling
	2. Recursive Feature Addition
	3. Probe Features
	4. MRMR
	5. Boruta

## Buy the Book

- [Book](https://www.trainindata.com/p/feature-selection-in-machine-learning-book)

## Setup

If you want to run the recipes of this book in a dedicated environment:

**Create and activate a virtual environment**
```bash
python -m venv fsmlbook
source fsmlbook/bin/activate        # macOS/Linux
fsmlbook\Scripts\activate           # Windows
```

**Install dependencies**
```bash
pip install -r requirements.txt
```

**Install Jupyter and register the kernel**
```bash
pip install jupyter ipykernel
python -m ipykernel install --user --name=fsmlbook --display-name "fsmlbook"
```

The environment will now be available as a kernel named **fsmlbook** in Jupyter Notebook.