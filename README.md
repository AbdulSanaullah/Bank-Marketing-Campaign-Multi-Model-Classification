# 🏦 Bank Marketing Campaign Success Prediction

A machine learning project that predicts whether a customer is likely to **subscribe to a bank term deposit** based on demographic, financial, and previous campaign information.

The project follows an end-to-end ML workflow, including **data analysis, preprocessing, feature engineering, model training, cross-validation, hyperparameter tuning, and model comparison**.

## 🎯 Problem

Banks often contact large numbers of customers during marketing campaigns, but not every customer is equally likely to subscribe.

This project aims to answer:

> **Can we predict whether a customer will subscribe to a term deposit based on their available customer and campaign information?**

A predictive model can help banks identify high-potential customers and make marketing campaigns more efficient.

## 📊 Dataset

The project uses the **Bank Marketing Dataset**.

**Target:** `deposit`

* `yes` → Customer subscribed
* `no` → Customer did not subscribe

Features include:

* Age, job, marital status, education
* Account balance
* Loans and default status
* Contact type and campaign information
* Previous campaign outcome
* Number of contacts and previous contacts

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Exploratory Data Analysis
   ↓
Feature Engineering
   ↓
Encoding & Scaling
   ↓
Train/Test Split
   ↓
Model Training
   ↓
Cross-Validation & Tuning
   ↓
Model Comparison
   ↓
Final Model
```

## 🤖 Models

Four classification algorithms were implemented:

| Model         |   Accuracy |
| ------------- | ---------: |
| KNN           |     82.00% |
| Naive Bayes   |     72.01% |
| Decision Tree |     78.77% |
| **SVM**       | **85.54%** |

Evaluation was based on **Accuracy, Precision, Recall, F1-score, and Confusion Matrix**.

### 🏆 Best Model: SVM

SVM achieved the strongest overall performance among the tested models, with **85.54% accuracy**, making it the selected final model.

## 🛠️ Technologies

* **Python**
* **Pandas & NumPy** — data processing
* **Matplotlib & Seaborn** — visualization
* **Scikit-learn** — machine learning
* **Jupyter Notebook** — development environment

## 💼 Business Value

The model can help move marketing from:

```text
Contact Everyone
       ↓
    Prediction
       ↓
Identify High-Potential Customers
       ↓
Targeted Marketing
       ↓
Better Campaign Efficiency
```

Potential benefits include:

* Reduced unnecessary calls
* Better customer targeting
* Lower marketing costs
* Improved campaign efficiency

## 🚀 Future Improvements

Possible extensions include:

* Random Forest, XGBoost, and Gradient Boosting
* Advanced hyperparameter optimization
* ROC-AUC and Precision-Recall analysis
* Customer segmentation
* Model deployment with **Streamlit or FastAPI**

## 👨‍💻 Author

**Sana Ullah**
BS Computer Science | AI, ML and DL

---

⭐ If you find this project useful, feel free to explore the notebook and experiment with different models and preprocessing techniques.
