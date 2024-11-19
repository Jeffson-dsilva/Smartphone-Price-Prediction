# Smartphone-Price-Prediction

This project involves building a machine learning model to predict mobile phone prices based on various features. The dataset contains details such as ratings, RAM, ROM, camera specifications, battery power, and more. The project includes data preprocessing, exploratory data analysis (EDA), and training multiple machine learning models to achieve the best performance.

## Features
The dataset includes the following columns:
- Ratings: User ratings of the mobile phone.
- RAM: Amount of RAM (in GB).
- ROM: Amount of internal storage (in GB).
- Mobile_Size: Size of the mobile screen (in inches).
- Primary_Cam: Resolution of the primary camera (in MP).
- Selfi_Cam: Resolution of the selfie camera (in MP).
- Battery_Power: Battery capacity (in mAh).
- Price: Mobile phone price (target variable).
## Steps Implemented
### 1. Data Preprocessing
- Identified and handled missing values:
 -  Filled missing values in numerical columns (Ratings, RAM, ROM, Mobile_Size) with their median.
 -  Filled missing values in the Selfi_Cam column with 0.
- Removed irrelevant columns.
### 2. Exploratory Data Analysis (EDA)
- Visualization:
  - Price distribution histogram.
  - Selfie camera count plot.
  - Correlation heatmap to analyze relationships between features.
  - Box plot showing the distribution of price by RAM size.
Identified key trends and relationships to guide feature engineering and model selection.
### 3. Model Training
Trained and evaluated the following models:

- Linear Regression:
  R² Score: 0.4729
  MAE: 9708.14
  RMSE: 16486.68
- Random Forest:
  R² Score: 0.8386
  MAE: 2796.14
  RMSE: 9125.10
- Gradient Boosting:
  R² Score: 0.8524
  MAE: 3070.66
  RMSE: 8726.01
#### Best Model: Gradient Boosting achieved the highest R² score (85%) and the lowest RMSE.

### 4. Visualization of Predictions
Scatter plots comparing actual prices vs. predicted prices for Gradient Boosting and Random Forest models.
