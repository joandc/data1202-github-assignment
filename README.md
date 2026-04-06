# DATA 1200 Assignment

## SVM and Naive Bayes Classification on the Raisin Dataset

### Course Information

- Course: `DATA 1200`
- Assignment: `Machine Learning Classification`
- Topic: `Support Vector Machine and Gaussian Naive Bayes`

This repository contains a Jupyter Notebook assignment that explores the `Raisin_Dataset.csv` dataset and compares two classification models:

- Support Vector Machine (SVM)
- Gaussian Naive Bayes

The notebook performs basic exploratory data analysis, visualizes feature relationships, prepares the data for modeling, and evaluates both classifiers.

## Repository Contents

- `Assignment-Data1200.ipynb` - main notebook for the assignment
- `Raisin_Dataset.csv` - raisin classification dataset used in the analysis
- `README.md` - project overview and usage instructions

## Tools and Libraries

The notebook uses the following Python libraries:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

## Installation

Install the following Python packages before running the notebook:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn notebook
```

## How To Run

1. Open a terminal in this project folder.
2. Start Jupyter Notebook:

```bash
jupyter notebook
```

3. Open `Assignment-Data1200.ipynb`.
4. Run the cells from top to bottom.

## Analysis and Model Evaluation

The notebook produces:

- summary statistics for the dataset
- a correlation heatmap
- a pairplot colored by class
- confusion matrices for each model
- classification reports for each model

## Expected Learning Outcomes

This assignment helps demonstrate how to:

- explore a structured dataset using descriptive statistics
- visualize relationships between variables
- prepare data for machine learning
- apply feature scaling before model training
- compare multiple classification algorithms
- evaluate model performance with confusion matrices and classification reports

## Sample Screenshots

![Sample Data](images/sampleData.png)

![Correlation Heatmap](images/heatmap.png)

## Purpose

This assignment demonstrates a basic machine learning workflow for binary classification, including:

- exploratory data analysis
- feature scaling
- train/test splitting
- model comparison
- performance evaluation

