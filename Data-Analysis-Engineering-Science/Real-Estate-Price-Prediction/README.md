
📌 Real Estate Price Prediction Project (Fabric - PySpark)

Objective: Develop a machine learning model that predicts real estate prices based on historical data, using both Linear Regression and Random Forest Regression to compare performance.

1️ Data Collection & Preprocessing

✔ Load the dataset (Real estate.csv) into Fabric’s Lakehouse environment. ✔ Identify missing values and clean data using PySpark functions. ✔ Prepare features for analysis, ensuring data integrity.

2️ Feature Engineering & Data Transformation

✔ Compute price per square meter for better comparisons. ✔ Categorize MRT proximity (Near, Medium, Far) for location analysis. ✔ Analyze pricing trends across different transaction dates and locations.

📊 Model Definitions

Linear Regression

✔ Assumes a straight-line relationship between features and price. ✔ Uses coefficients to determine how much each feature impacts predictions. ✔ Works well for simple trends but struggles with complex patterns. Random Forest Regression

✔ Uses multiple decision trees to capture non-linear relationships. ✔ Provides feature importance scores instead of coefficients. ✔ Reduces overfitting and performs better with complex pricing structures.

4️ Model Evaluation & Feature Importance

✔ Calculate RMSE & R-squared (R²) to compare accuracy. ✔ Linear Regression → Uses coefficients to show feature impact. ✔ Random Forest → Uses feature importance scores to rank predictors.

5️ Predictions Visualization ✔ Plot Actual vs Predicted Prices using scatter plots. ✔ Identify residuals and prediction errors. ✔ Random Forest typically has lower RMSE, indicating higher accuracy.

🔍 Key Differences Between Models Model Strengths Limitations Linear Regression Simple, interpretable Struggles with complex patterns Random Forest Regression Handles non-linearity, reduces overfitting Harder to interpret feature relationships

💡 Which Model is Better? ✔ If trends are linear, Linear Regression is sufficient. ✔ If data is complex, Random Forest captures better pricing trends.
