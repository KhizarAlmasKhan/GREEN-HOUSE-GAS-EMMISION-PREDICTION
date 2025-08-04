# GREEN-HOUSE-GAS-EMMISION-PREDICTION

# 🌱 Greenhouse Gas Emission Prediction using Data Quality Metrics

A Machine Learning-based project to predict Supply Chain Emission Factors using historical data (2010–2016), incorporating both descriptive and data quality metrics to support sustainable and data-driven decision-making.

---

## 👨‍💻 Author

**Mohammed Khizar Almas Khan**  
[GitHub Profile](https://github.com/KhizarAlmasKhan)

---

## 📌 Project Objectives

- Predict **Supply Chain Emission Factors with Margins** using supervised learning.
- Leverage descriptive features (e.g., `Substance`, `Unit`) and data quality indicators:
  - `Reliability`
  - `Temporal Correlation`
  - `Geographical Correlation`
  - `Technological Correlation`
  - `Data Collection Methodology`
- Apply and compare regression models with and without hyperparameter tuning.

---

## 🧰 Technologies Used

| Purpose           | Libraries / Tools         |
|------------------|---------------------------|
| Data Processing  | `pandas`, `numpy`         |
| Visualization    | `matplotlib`, `seaborn`   |
| ML Modeling      | `scikit-learn`            |
| Model Tuning     | `GridSearchCV`            |
| Evaluation       | `r2_score`, `mean_squared_error` |
| Deployment       | `joblib` (for model saving) |

---

## 🔍 Methodology

1. **Data Acquisition:** Loaded multi-year Excel files (2010–2016).
2. **Data Cleaning:** Removed irrelevant columns, handled nulls.
3. **Feature Engineering:** Encoded categorical features using `LabelEncoder`.
4. **Feature Scaling:** Standardized numerical features using `StandardScaler`.
5. **Modeling:**
   - Trained `RandomForestRegressor`, `GradientBoostingRegressor`, and `LinearRegression`.
6. **Hyperparameter Tuning:** Optimized Random Forest using `GridSearchCV`.
7. **Evaluation:** Compared models using **RMSE** and **R² Score**.
8. **Model Saving:** Saved best model and scaler using `joblib`.

---

## 📊 Screenshots

### 1. Data Analysis & Visualization
*(Insert charts from your notebook: feature distributions, correlation matrices, etc.)*

### 2. Before vs After Hyperparameter Tuning  
📎 `before_after_tuning.png` (comparison bar chart of RMSE and R² Score)


---

## ✅ Results

- Final tuned model outperformed baseline models in both RMSE and R² metrics.
- Demonstrated measurable improvement through hyperparameter tuning.
- Identified key drivers of supply chain emissions via feature importance.
- Validated the impact of preprocessing and tuning on prediction accuracy.

---

## 📦 Installation

```bash
# Clone the repo
git clone https://github.com/KhizarAlmasKhan/GREEN-HOUSE-GAS-EMMISION-PREDICTION.git

---

## 📃 License

This project is for academic and research purposes. Attribution appreciated.