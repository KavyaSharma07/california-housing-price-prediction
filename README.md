# 🏡 California House Price Prediction

A machine learning project to predict house prices in California using key features like income, house age, rooms, and geographical location.

📓 [View the notebook](./housing_price_prediction.ipynb)

---

## 🔍 Problem Statement
The goal is to build a regression model that accurately predicts house prices using features from the California Housing dataset. This includes demographic and geographic data.

---

## 📂 Dataset Used
- Source: `fetch_california_housing()` from Scikit-learn
- Includes 8 features and a target price value.

---

## 🛠️ Tools & Technologies
- Python
- Pandas & NumPy
- Matplotlib & Seaborn (for visualization)
- Scikit-learn (for modeling & evaluation)
- Google Colab (notebook environment)

---

## 🚀 ML Workflow

1. **Data Loading & Initial Inspection**
2. **Exploratory Data Analysis**
3. **Correlation Heatmap & Feature Selection**
4. **Model Building:**
   - Linear Regression
   - Random Forest Regressor
5. **Model Evaluation:**
   - Mean Absolute Error (MAE)
   - Root Mean Squared Error (RMSE)
   - R² Score
6. **Visualization:**
   - Actual vs Predicted Price Plot
   - Feature Importance Bar Chart

---

## 📊 Evaluation Metrics

| Metric | Linear Regression | Random Forest |
|--------|-------------------|----------------|
| R²     | 0.58              | 0.81 ✅         |
| MAE    | —                 | 0.33 ✅         |
| RMSE   | —                 | 0.50 ✅         |

---

## 📈 Key Insights

- `MedInc` (Median Income) was identified as the most important feature based on feature importance analysis.
- `HouseAge` and `AveRooms` also showed meaningful influence on predicted house prices.
- Random Forest outperformed Linear Regression, indicating that the data contains non-linear relationships.
- Correlation analysis and visualizations helped identify relationships between features and the target variable.

---

## 🖼️ Visualizations

- Correlation Heatmap
- Feature Importance Plot
- Predicted vs Actual Price Graph

---

## ✅ Outcome

- Successfully trained and evaluated two models.
- Random Forest produced the best results.
- Exported feature importance visualization for reporting.
- Great project to showcase ML workflow in resume & GitHub.

---

## ✨ Author

**Kavya Sharma**  
Aspiring Machine Learning Engineer  
