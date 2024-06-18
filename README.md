# Predicting PM2.5 Levels in African Cities with CatBoost and Satellite Data (Zindi Competition)

This repository tackles a crucial environmental challenge: predicting PM2.5 (particulate matter with a diameter less than 2.5 micrometers) levels in eight African cities using satellite imagery and the CatBoost algorithm. This project is based on data provided for the Zindi competition "[Competition Name]" (replace with the actual competition name). Accurately estimating PM2.5 concentrations empowers individuals and authorities to take proactive measures towards cleaner air.

## Dataset
This project utilizes a custom dataset specifically designed for a ompetition in Zindi platform, focusing on predicting PM2.5 levels in the following eight African cities across seven countries:

- Kampala, Uganda
- Lagos, Nigeria
- Accra, Ghana
- Nairobi, Kenya
- Yaoundé, Cameroon
- Bujumbura, Burundi
- Kisumu, Kenya
- Gulu, Uganda

The dataset combines:
- PM2.5 measurements (ground truth)
- Satellite-derived Aerosol Optical Depth (AOD) data
- Information on atmospheric pollutants (SO2, CO, NO2, HCHO, UvAI, O3, Cloud Cover) extracted from Sentinel-5P satellites

## Key Techniques
- **Data Preprocessing:** Thorough data cleaning, handling missing values, and potential feature scaling for normalization.
- **Feature Engineering:** Creation of informative features from satellite imagery and other data to enhance model performance.
- **CatBoost Modeling:** Leveraging the CatBoost algorithm's efficiency and ability to handle diverse data types for accurate PM2.5 prediction.
- **Group K-Fold Cross-Validation:** Ensuring model generalizability on unseen data through robust evaluation.
- **Evaluation and Analysis:** Utilizing metrics like Root Mean Squared Error (RMSE) to assess model accuracy and feature importance analysis to identify key influencing factors.

## Expected Outcomes
A reliable CatBoost model for predicting PM2.5 levels in African cities using satellite observations.



