🏠 California Housing Price Prediction with XGBoost

This project is an end-to-end machine learning study developed to predict house prices using the California housing dataset. The main focus of the project is not merely achieving a high score, but ensuring that the model generalizes well to real-world data.

🚀 Project Highlights

Comprehensive Exploratory Data Analysis (EDA): Data distributions, location-based visualizations, and correlation analyses.

Feature Engineering: Model performance was improved by deriving more meaningful features from raw data (e.g., rooms per household).

Outlier Handling: Noisy values in the target variable were removed using the IQR method.

Model Comparison: Models such as Linear Regression, Random Forest, and AdaBoost were compared against XGBoost.

Hyperparameter Optimization: Optimal parameters were identified using RandomizedSearchCV.

⚖️ Strategic Decision: Overfitting Control

In this project, instead of choosing a highly complex model that achieved a 98% R² score on the training set, a baseline XGBoost model with a more balanced relationship between training and test scores (Train: 0.87, Test: 0.82) was preferred. This decision was made to prevent overfitting and to produce more reliable predictions.

🛠️ Technologies Used

Language: Python

Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

📊 Results

Final Test R² Score: 0.82

Final RMSE: ~42,000 $
