# Polymer Property Prediction using Molecular Feature Engineering and Machine Learning

## Overview

This project was developed for the **NeurIPS 2025 Open Polymer Prediction Challenge**.  
It combines computational chemistry and machine learning to predict polymer properties from molecular structures.  
The approach focuses on chemistry-aware feature engineering and ensemble learning to improve predictive accuracy and interpretability.

Traditional ML models often perform poorly on chemical data because raw molecular identifiers fail to capture real-world structural interactions.  
To address this, this project introduces a domain-informed pipeline that transforms molecular representations into rich, interpretable features and employs advanced boosting algorithms to predict target polymer properties.

---

## Key Features

### Chemistry-Driven Feature Engineering
- Integrated **RDKit** to compute physicochemical and structural molecular descriptors.  
- Generated **Morgan fingerprints** to capture substructure and molecular similarity.  
- Modeled molecular structures as graphs using **NetworkX** to extract topological descriptors.  
- Combined chemically meaningful features for improved model generalization and interpretability.

### Advanced Machine Learning Modeling
- Compared and fine-tuned multiple ensemble models: **XGBoost**, **CatBoost**, **LightGBM**, **RandomForest**, and **ExtraTrees**.  
- Used **Optuna** for automated hyperparameter optimization, minimizing **Mean Absolute Error (MAE)**.  
- Applied **K-Fold Cross-Validation** to ensure robust and stable performance estimates.

### Visualization and Analysis
- Performed **Exploratory Data Analysis (EDA)** using Seaborn and Matplotlib.  
- Analyzed feature–target relationships, correlation patterns, and data distributions.  
- Visualized model performance, feature importance, and residual error distributions to support interpretability.

### Modular and Reproducible Design
- Organized data processing, feature extraction, and modeling steps into clear, modular scripts.  
- Fully reproducible setup with:
  - `requirements.txt` for environment setup  
  - Well-documented **README.md** for guidance  
  - Jupyter notebooks for exploration and validation  

---

## Tech Stack

| Category | Tools / Libraries |
|-----------|-------------------|
| **Language** | Python |
| **ML Frameworks** | XGBoost, LightGBM, CatBoost, scikit-learn |
| **Chemistry Tools** | RDKit |
| **Optimization** | Optuna |
| **Graph Analysis** | NetworkX |
| **Visualization** | Seaborn, Matplotlib |
| **Environment** | Jupyter Notebook / Kaggle |

---

## Outcome

By integrating chemical domain knowledge with machine learning, this project demonstrates how feature engineering enhances predictive accuracy in materials informatics.  
The resulting pipeline is scalable, interpretable, and well-suited for polymer and molecular property prediction tasks.  
It provides a practical framework for exploring structure–property relationships and accelerating materials discovery.

---

## Project Structure

