# Multiple Linear Regression

This notebook demonstrates a clean implementation of **Multiple Linear Regression** using the **California Housing** dataset.  
It predicts median house values based on several features like average income, house age, population, and more.

---

## 📈 What You'll Learn

- How to apply multiple linear regression using scikit-learn  
- How to scale features properly for regression  
- How to evaluate the model using key metrics  
- How to visualize residuals and predictions  
- How to save your model for deployment  


## 🧠 Model Type

- **Algorithm**: Multiple Linear Regression
- **Library**: `LinearRegression` from `scikit-learn`
- **Problem Type**: Supervised regression

---

## 📊 Dataset

- **Source**: `fetch_california_housing()` from `scikit-learn.datasets`
- **Features**:
  - `MedInc`, `HouseAge`, `AveRooms`, `AveBedrms`, `Population`, `AveOccup`, `Latitude`, `Longitude`
- **Target**: `MedHouseVal` — Median house value

---

## 📂 Files Included

- `Multiple_linear_regression.ipynb`:  
  The Jupyter notebook that walks through:
  - Data loading with `fetch_california_housing()`
  - Feature scaling using `StandardScaler`
  - Train/test splitting
  - Model training using `LinearRegression`
  - Evaluation with metrics like MAE, MSE, and R²
  - Visualizations and model saving with `pickle`

---

## 🔧 Dependencies

Install the required Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
