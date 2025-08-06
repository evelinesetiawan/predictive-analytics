# 🚀 Predicting Airbnb Price Listing in Melbourne

# 📌 Table of Contents
1. About the Project
2. Dataset
3. Key Objectives
4. Workflow Overview
5. Technology Stack
6. Project Highlights

# 🔍 About the Project
This repository contains the submission for the ASBA Predictive Analytics Competition (2025) on Kaggle. The aim was to build a predictive model estimating Airbnb listing prices in Melbourne, using real listing features. This challenge was contributed by a team consist of 3 people: me, **Rachel Tran** and **Merlyn Febriany**, replicating a full analytical workflow, imaging real-world business forecasting.

# 🗂 Dataset
- Training set: 7,000 records
- Test set: 3,000 records (no price labels)
- Target: price (numeric, in AUD)
- Evaluation metric: Mean Absolute Error (MAE), the lower the number, the better.
  
# 🎯 Key Objectives
- Understand and prepare the Airbnb listing data
- Engineer meaningful features (e.g. location, room type, number of amenities)
- Build regression models to minimise MAE
- Validate results via Kaggle’s public and final leaderboard

# 🧠 Workflow Overview

| Stage               | Description |
|---------------------|-------------|
| **Data Cleaning**   | Handle missing values, format categorical variables, remove outliers |
| **EDA**             | Visualise price distribution, room type, neighbourhood trends |
| **Feature Engineering** | Create features like location clusters, amenity counts, review score categories |
| **Modelling**        | Tried XGBoost, LightGBM, RandomForest, and stacked ensembles |
| **Model Evaluation**| Validate using cross‑validation, track performance on Kaggle’s public leaderboard |
| **Submission**      | Generate submission CSV and track final leaderboard MAE |

# 🛠️ Technology Stack
- Languages: Python, Jupyter Notebook
- Libraries: pandas, NumPy, scikit-learn, XGBoost, LightGBM, matplotlib, geopandas
- Platform: Kaggle Notebooks & local development environment

# 📈 Project Highlights
In this project, we achieved a train MAE of 1.25784 and a test MAE of 268.168 on the public leaderboard (final ranking: #1 / ~500 participants) using XGBoost regression. Further, we dive deeper on how price variation across Melbourne suburbs reveal strong correlations with certain accomodation features.
