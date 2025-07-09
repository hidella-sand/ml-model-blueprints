# Logistic Regression Variants

This folder contains multiple implementations of **Logistic Regression**, covering a range of real-world scenarios — from binary classification to handling imbalanced datasets and evaluating models with ROC-AUC.

---

## 📘 What You'll Learn

- How logistic regression works for binary and multi-class problems  
- How to train and evaluate logistic regression models using scikit-learn  
- How to deal with imbalanced datasets using class weighting and resampling  
- How to use metrics like accuracy, precision, recall, and F1-score  
- How to plot and interpret ROC curves and calculate AUC  
- The importance of proper evaluation based on dataset characteristics  

## 📂 Included Notebooks

### 1. 🧪 Binary Logistic Regression
- Trains a basic logistic regression model on a binary classification dataset.
- Demonstrates data preprocessing, training, and performance evaluation.
- Introduces concepts like decision boundaries and sigmoid activation.

### 2. ⚖️ Logistic Regression on Imbalanced Dataset
- Shows how to handle imbalanced class distributions effectively.
- Explores methods like:
  - Resampling techniques
  - Using `class_weight='balanced'`
- Evaluates impact of imbalance on accuracy vs. precision/recall.

### 3. 🎯 Multi-Class Logistic Regression
- Implements one-vs-rest (OvR) or softmax logistic regression for multi-class targets.
- Evaluates predictions with multi-class confusion matrix and classification report.

### 4. 📉 ROC-AUC Evaluation
- Focuses on evaluating binary classifiers using:
  - ROC curve
  - AUC score
- Helps visualize the trade-off between true positive rate and false positive rate.

---

## 🛠️ Dependencies

Install the required packages using:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
