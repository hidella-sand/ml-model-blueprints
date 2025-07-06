# Simple Linear Regression

This project demonstrates a clean and minimal implementation of **Simple Linear Regression** using Python and scikit-learn.  
It uses a dataset of height and weight to predict a person's weight based on their height.

---


## 📈 What You'll Learn

- The intuition behind simple linear regression  
- How to apply it using scikit-learn  
- How to evaluate its accuracy  
- How to visualize predictions and model performance  
- How to save a trained model for future use


## 📊 Dataset

- **File**: `height-weight.csv`
- **Columns**:
  - `Height`: The height of individuals (in inches)
  - `Weight`: The weight of individuals (in pounds)
- This is a synthetic dataset commonly used for linear regression tutorials.

---

## 📂 Files Included

- `Simple Linear Regression Model.ipynb`:  
  A Jupyter Notebook that walks through:
  - Data import and exploration
  - Train-test split
  - Feature scaling (optional)
  - Training a linear regression model
  - Evaluating performance using metrics like MAE, MSE, and R²
  - Visualizing regression line
  - Saving the model using `pickle`

- `height-weight.csv`:  
  The dataset used in the notebook (ensure it's in the same folder).

---

## 📌 Dependencies

Install the required packages with:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
