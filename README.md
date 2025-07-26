🌍 Greenhouse-Gas-Emission-Prediction
📅 Week 1: Data Preparation & Modeling
This project uses 2010–2016 U.S. supply chain emission data to build a regression model that predicts Supply Chain Emission Factors with Margins based on industry, substance, and data quality metrics.

🔧 Key Steps
Data Cleaning: Removed irrelevant columns and null values

Feature Encoding: One-hot encoded categorical features (Industry Name, Substance, Unit)

Model Saving: Exported best-performing model as .pkl using joblib

🎯 Output
Cleaned dataset and trained ML model

📅 Week 2: Model Tuning & Evaluation
In Week 2, we focused on improving model performance and robustness by optimizing parameters and conducting deeper evaluation.

⚙️ Key Steps
Train-Test Split: Created test and validation sets using train_test_split

Hyperparameter Tuning: Used GridSearchCV to optimize DecisionTreeRegressor parameters

Evaluation Metrics: Compared models using:

-R² Score

-Mean Absolute Error (MAE)

-Mean Squared Error (MSE)

🧠 Best Performing Model
DecisionTreeRegressor with tuned parameters showed improved accuracy

Model was saved as .pkl for deployment

📁 Output
Evaluation report of models

Optimized .pkl file for predictions













### 📁 Dataset

[📄 Download the dataset (CSV)](https://github.com/ArpitaSingh123/Greenhouse-Gas-Emission-Prediction/raw/refs/heads/main/SupplyChainEmissionFactorsforUSIndustriesCommodities2015_Summary.csv)


