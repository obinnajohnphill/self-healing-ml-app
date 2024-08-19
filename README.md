# Self-Healing Machine Learning Application

This repository contains a self-healing machine learning application written in Python using Jupyter Notebooks. The application is designed to analyse system logs, classify errors and warnings, and trigger self-healing actions based on the results.

## Overview

The application processes log data from various systems (macOS, Android, Linux, and Windows), performs data preprocessing and tokenisation, and applies classification models to identify and classify errors and warnings. Based on the classifications, the system can trigger self-healing actions to mitigate issues automatically.

### Key Features

- **Log Data Extraction**: Extracts log data from various system types.
- **Data Preprocessing**: Cleans, preprocesses, and tokenises the log data for further analysis.
- **Model Analysis and Classification**: Applies classification models to identify and classify errors and warnings.
- **Self-Healing Triggers**: Automatically triggers self-healing processes based on the classification results.

## Jupyter Notebooks

The following Jupyter Notebooks are included in this repository:

- `analysis-of-errors-and-warning-statistics.ipynb`: Statistical analysis of errors and warnings across different systems.
- `android-data-classification-model-analysis.ipynb`: Classification model analysis for Android system logs.
- `classification_analysis.ipynb`: General classification analysis across systems.
- `classify-errors-and-trigger-self-healing.ipynb`: Classifies errors and warnings and triggers self-healing actions.
- `error-and-warning-counts.ipynb`: Counts and analyses the frequency of errors and warnings.
- `error-classification.ipynb`: Focused classification of error logs.
- `extracted-and-preprocessed-data.ipynb`: Data extraction and preprocessing from system logs.
- `linux-data-classification-model-analysis.ipynb`: Classification model analysis for Linux system logs.
- `log-extraction.ipynb`: Extraction of log data from various systems.
- `mac-data-classification-model-analysis.ipynb`: Classification model analysis for macOS system logs.
- `model-analysis-and-comparison.ipynb`: Comparison of different classification models.
- `preprocessing.ipynb`: Detailed preprocessing steps for log data.
- `windows-data-classification-model-analysis.ipynb`: Classification model analysis for Windows system logs.

## Datasets

Due to space constraints on GitHub, the datasets containing real system logs for macOS, Android, Linux, and Windows could not be included in this repository. These datasets can be downloaded separately from Zenodo:

[Download Dataset from Zenodo](https://zenodo.org/records/3227177#.ZEwlc-zMJhE)

## How to Use

1. Clone this repository to your local machine.
2. Download the datasets from Zenodo and place them in the appropriate directories.
3. Open the Jupyter Notebooks and follow the instructions to run the analysis and classification models.

## Requirements

- Python 3.x
- Jupyter Notebook
- Required Python libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

You can install the required libraries using pip:

```bash
pip install -r requirements.txt
