# AdaBoost Regression for Water Pollutant Degradation Prediction

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/)
[![Scikit-learn](https://img.shields.io/badge/scikit--learn-0.24-green)](https://scikit-learn.org/)
[![License](https://img.shields.io/badge/License-MIT-lightgrey)](LICENSE)

## 📖 Project Overview

**Predicting Water Pollutant Degradation Using AdaBoost Regression**

Water pollution poses a significant threat to ecosystems and human health. Effective remediation strategies rely on accurate predictions of contaminant degradation. This project develops and evaluates an ensemble-based regression model to forecast pollutant breakdown under varying laboratory conditions.

---

## 🔬 Abstract

> Experimental data — pollutant concentration, temperature, pH, and other process variables — were preprocessed to handle missing values and normalized for analysis. Multiple train–test splits were compared, with 60:40 yielding the best balance.
>
> The core algorithm is AdaBoost regression (scikit-learn), benchmarked against XGBoost, ANFIS, ANN, and hybrid GA‑ANFIS/PSO‑ANFIS. Hyperparameters (estimators 20–300, learning rate, base estimator depth) were tuned to minimize RMSE. Default AdaBoost base estimator outperformed tree variants, reducing RMSE by over 15% compared to untuned models.
>
> AdaBoost offers a superior balance of accuracy, interpretability, and efficiency. While deep-learning and fuzzy-logic hybrids sometimes achieved marginally lower errors, they required heavier tuning and longer training. All experiments, metrics, and code artifacts are documented for full reproducibility.
>
> This work validates AdaBoost regression as a robust tool for environmental modeling and provides a transparent workflow for future water pollution forecasting studies.

---

## ⚙️ Features

- **Data Preprocessing**: Handles missing values, normalization, and train-test split utilities.
- **Model Training**: Implements AdaBoost regression with configurable base estimators.
- **Benchmarking**: Compare performance against XGBoost, ANFIS, ANN, GA‑ANFIS, and PSO‑ANFIS.
- **Hyperparameter Tuning**: Grid search over estimator counts, learning rates, and depths to minimize RMSE.
- **Visualization**: Learning curves, feature importance, and error distribution plots.
- **Reproducibility**: All settings and metrics are logged; random seeds fixed.

---

## 🚀 Getting Started

### Prerequisites

- Python 3.8 or higher
- pip

### Installation

```bash
# Clone the repository
$ git clone https://github.com/ArefCheraghali/AdaBoost.git
$ cd AdaBoost

# Create a virtual environment (optional)
$ python -m venv venv
$ source venv/bin/activate  # On Windows use `venv\\Scripts\\activate`

# Install dependencies
$ pip install -r requirements.txt
