Polymer Property Prediction using Molecular Feature Engineering and Machine Learning:

This project blends computational chemistry with machine learning to predict polymer properties using molecular structure data.
It was developed for the NeurIPS 2025 Open Polymer Prediction Challenge, aiming to extract deep chemical insights through feature engineering and ensemble learning.

Project Overview:

Traditional machine learning models struggle with chemical data because raw molecular identifiers fail to capture real-world interactions.
To solve this, I engineered a chemistry-aware pipeline that transforms molecular representations into rich, interpretable features, then uses advanced boosting models to predict target polymer properties.

Key Features:

Chemistry-Driven Feature Engineering
Integrated RDKit to compute physicochemical and structural molecular descriptors.
Generated Morgan fingerprints and graph-based features representing atomic connectivity and substructure similarity.
Employed NetworkX to model molecular graphs and derive topological statistics.
Advanced ML Modeling
Compared and fine-tuned XGBoost, CatBoost, LightGBM, RandomForest, and ExtraTrees regressors.
Used Optuna for automated hyperparameter optimization, minimizing Mean Absolute Error (MAE).
Validated models with K-Fold Cross-Validation for stable performance estimates.
Visualization and Analysis
Conducted detailed EDA using Seaborn and Matplotlib to uncover relationships between chemical features and target values.
Visualized model performance and error distributions for interpretability.
Modular and Reproducible Design
Organized clean data processing and modeling pipelines.
Includes all dependencies via requirements.txt and clear README instructions for easy reproduction.
Tech Stack:

Languages: Python
Libraries: RDKit, scikit-learn, XGBoost, LightGBM, CatBoost, Optuna, NetworkX, Seaborn, Matplotlib
Environment: Kaggle / Jupyter Notebook
Outcome:

By merging chemical intuition with data-driven modeling, this project demonstrates how domain knowledge can amplify predictive accuracy in materials informatics.
It provides a scalable and interpretable pipeline for future polymer and molecular property prediction challenges.

