# Advanced Machine Learning: Health Data Analysis Project

## Overview

This repository contains a group project for the Advanced Machine Learning (AML) course at UT Austin's MSBA program. The project analyzes health-related behavioral data from the UCI BRFSS (Behavioral Risk Factor Surveillance System) dataset to develop predictive models for health outcomes.

## Project Workflow

The project follows a structured machine learning pipeline:

1. **Data Merging** (`notebooks/data_merging.ipynb`)
   - Combines multiple data sources
   - Loads and integrates UCI BRFSS datasets
   - Prepares raw data for processing

2. **Data Cleaning & Feature Engineering** (`notebooks/Data Cleaning and Feature Engineering.ipynb`)
   - Handles missing values and outliers
   - Creates meaningful features from raw data
   - Performs feature selection and transformation
   - Prepares data for modeling

3. **Exploratory Data Analysis** (`notebooks/AML_EDA.ipynb`)
   - Analyzes data distributions and relationships
   - Visualizes key patterns in health behaviors
   - Identifies correlations and interactions
   - Informs feature importance

4. **Modeling & Evaluation** (`notebooks/AML_Modeling_Evaluation.ipynb`)
   - Implements multiple machine learning algorithms
   - Evaluates model performance using various metrics
   - Compares different approaches
   - Selects optimal models

## Repository Structure

```
aml_presentation/
├── notebooks/                          # Jupyter notebooks with analysis code
│   ├── data_merging.ipynb
│   ├── Data Cleaning and Feature Engineering.ipynb
│   ├── AML_EDA.ipynb
│   └── AML_Modeling_Evaluation.ipynb
├── docs/                               # Project documentation and presentations
│   ├── Group 19 Project Proposal.pdf
│   └── Condensed_Presentation_Text.docx
└── README.md                           # This file
```

## Opening Notebooks in Google Colab

All notebooks can be opened directly in Google Colab for interactive analysis:

- [data_merging.ipynb](https://colab.research.google.com/github/AHMerrill/aml_presentation/blob/main/notebooks/data_merging.ipynb)
- [Data Cleaning and Feature Engineering.ipynb](https://colab.research.google.com/github/AHMerrill/aml_presentation/blob/main/notebooks/Data%20Cleaning%20and%20Feature%20Engineering.ipynb)
- [AML_EDA.ipynb](https://colab.research.google.com/github/AHMerrill/aml_presentation/blob/main/notebooks/AML_EDA.ipynb)
- [AML_Modeling_Evaluation.ipynb](https://colab.research.google.com/github/AHMerrill/aml_presentation/blob/main/notebooks/AML_Modeling_Evaluation.ipynb)

## Key Technologies

- **Python 3** with pandas, NumPy, scikit-learn
- **Jupyter Notebooks** for interactive analysis
- **Machine Learning Models** for predictive analytics
- **Data Visualization** for insights and presentations

## Group Members

Group 19 - UT Austin MSBA Advanced Machine Learning

## License

This project was completed as part of the UT Austin MSBA program curriculum.
