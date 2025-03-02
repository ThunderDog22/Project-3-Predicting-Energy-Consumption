# Project-3-Predicting-Energy-Consumption

Overview:
Energy efficiency is crucial for sustainable urban planning. This project develops machine learning models to predict electricity consumption (kWh) of buildings using various structural and operational features.

We experimented with Random Forest, XGBoost, and category-specific models to improve prediction accuracy.

📊 Data Source: The dataset is publicly available at:
https://data.seattle.gov/Built-Environment/Building-Energy-Benchmarking-Data-2015-Present/teqw-tu6e/data_preview

🛠️ Machine Learning Models
The following models were trained and evaluated:
✅ Random Forest Regressor
✅ XGBoost Regressor
✅ Category-Specific XGBoost Models (separate models per building type)

📌 Train-Test Split: 80% Training, 20% Testing
📌 Evaluation Metrics:

R² Score (higher is better)
Root Mean Squared Error (RMSE) (lower is better)
Mean Absolute Error (MAE) (lower is better)
