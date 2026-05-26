# Student Stress Prediction using Smartphone Sensing Data

This project investigates whether daily stress levels among university students can be predicted using behavioral and self-reported smartphone sensing data from the StudentLife dataset. The project applies machine learning models to longitudinal behavioral data, including sleep, workload, social activity, physical activity, and mood-related variables.

## Project Overview

The analysis focuses on predicting daily stress levels using:

- Linear Regression
- Random Forest Regression

Several dataset configurations were evaluated:

- Behavioral features only
- Behavioral + mood valence features
- Reduced behavioral dataset matched to the mood dataset size

Model performance was evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² score
- Group K-Fold cross-validation

The project further includes:

- Feature importance analysis
- Descriptive statistics
- Dataset

**This project uses the StudentLife Dataset, originally collected at Dartmouth College as part of the StudentLife study.**

Dataset Reference

Wang, R., Chen, F., Chen, Z., Li, T., Harari, G., Tignor, S., Zhou, X., Ben-Zeev, D., & Campbell, A. T. (2014). StudentLife: Assessing mental health, academic performance and behavioral trends of college students using smartphones. Proceedings of the 2014 ACM International Joint Conference on Pervasive and Ubiquitous Computing. https://doi.org/10.1145/2632048.2632054

Dataset access:
StudentLife Dataset on Kaggle: https://www.kaggle.com/datasets/dartweichen/student-life 

