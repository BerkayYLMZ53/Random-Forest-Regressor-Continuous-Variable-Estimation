# 🌲 Continuous Variable Prediction with Random Forest Regressor

This project was developed to predict a continuous target variable using the **Random Forest Regressor**, an ensemble learning algorithm in machine learning.

## 🎯 Project Objective
To minimize the high variance and error rates that a single decision tree might produce by training multiple decision trees simultaneously (Bagging method), thereby generating more robust and stable regression predictions.

## 🎛️ Hyperparameter Optimization
The **`GridSearchCV`** framework was used to find the optimal number of trees (`n_estimators`), maximum depth (`max_depth`), and splitting criteria. This process helped optimize the model's parameters rather than relying on default configurations.

## 📈 Model Performance and Metrics
The trained Random Forest model was evaluated on the test data using the following performance and error metrics:
* **RMSE (Root Mean Squared Error):** `4374.65`
* **MAE (Mean Absolute Error):** `2540.50`
* **$R^2$ Score (Coefficient of Determination):** `0.8695` (explaining approximately 86.95% of the variance in the target variable).

## 🚀 Running the Project Locally
```bash
git clone https://github.com/BerkayYLMZ5353/random-forest-regression.git
pip install pandas numpy matplotlib seaborn scikit-learn
jupyter notebook RandomForest_Odev.ipynb
```
```
