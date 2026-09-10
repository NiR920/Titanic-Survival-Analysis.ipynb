# Titanic Survival Analysis

> An exploratory data analysis and machine-learning project investigating the factors associated with passenger survival on the Titanic.

[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter&logoColor=white)](h24mdnra%40du.se_Lab2.ipynb)
[![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-F7931E?logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)

## Overview

**Titanic Survival Analysis** uses the well-known Titanic passenger dataset to explore survival patterns and build a data-driven understanding of which passenger characteristics are associated with survival.

The project combines exploratory data analysis, data cleaning, feature preparation, visualization, and predictive modelling in a reproducible Jupyter Notebook workflow.

## Objectives

The analysis is designed to answer questions such as:

- Which passenger characteristics are most strongly associated with survival?
- How do factors such as passenger class, age, and sex relate to survival outcomes?
- Can a machine-learning model predict survival from the available passenger information?
- What are the strengths and limitations of the resulting predictions?

## Analytical Workflow

```text
Titanic Passenger Data
          │
          ▼
Data Inspection & Cleaning
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Feature Engineering
          │
          ▼
Model Training
          │
          ▼
Model Evaluation
          │
          ▼
Insights & Conclusions
```

## Repository Structure

```text
Titanic-Survival-Analysis.ipynb/
├── README.md
└── h24mdnra@du.se_Lab2.ipynb   # Main analysis and modelling notebook
```

## Getting Started

### Clone the repository

```bash
git clone https://github.com/NiR920/Titanic-Survival-Analysis.ipynb.git
cd Titanic-Survival-Analysis.ipynb
```

### Create a virtual environment

```bash
python -m venv .venv
```

Activate it with:

**macOS / Linux**
```bash
source .venv/bin/activate
```

**Windows PowerShell**
```powershell
.venv\Scripts\Activate.ps1
```

### Install dependencies

A typical environment for the notebook includes:

```bash
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
```

> The notebook remains the source of truth for the exact libraries and imports used in the analysis.

### Launch the notebook

```bash
jupyter notebook
```

Open `h24mdnra@du.se_Lab2.ipynb` and run the cells in order.

## What the Analysis Covers

### Data preparation

The dataset is inspected for missing values, data types, distributions, and other quality considerations before modelling.

### Exploratory analysis

Visual and statistical analysis is used to investigate relationships between passenger attributes and survival outcomes.

### Feature preparation

Relevant variables are prepared in a form suitable for predictive modelling, with appropriate treatment of categorical and numerical data.

### Predictive modelling

Machine-learning methods are applied to estimate survival outcomes from passenger information.

### Evaluation

Predictions are assessed using suitable classification metrics and interpreted alongside the exploratory findings.

## Key Insight Areas

The analysis focuses on the relative importance of passenger characteristics rather than treating survival as a purely random outcome. In particular, passenger class, sex, age, and related socioeconomic or demographic variables are natural candidates for investigation.

Exact findings and model scores should be taken from the executed notebook outputs.

## Reproducibility

For consistent results:

- Use a dedicated Python virtual environment.
- Keep package versions recorded for formal submissions or reports.
- Set random seeds where supported by the modelling workflow.
- Run preprocessing before training and evaluation cells.
- Preserve notebook outputs when publishing final results.

## Limitations

The Titanic dataset is a historical teaching dataset and should be treated as an educational example rather than a modern real-world prediction problem. Results are constrained by the available variables, missing information, historical context, and the modelling choices used in the notebook.

Model performance on this dataset should therefore not be interpreted as evidence of general predictive ability outside the dataset's original context.

## Academic Context

This repository is presented as an applied data-analysis and machine-learning lab project. The Jupyter Notebook is the primary implementation and documentation artifact.

## License

No license is currently declared for this repository. Add an appropriate license before redistributing the notebook or derived code.

## Author

**NiR920**

Repository: https://github.com/NiR920/Titanic-Survival-Analysis.ipynb
