# 📊 Telecom Customer Churn Prediction

This project focuses on predicting telecom customer churn using supervised machine learning models. It uses the Telco Customer Churn dataset, which contains information about customers' demographics, contract details, service usage, and billing history.

## 📁 Project Structure

```
CustomerChurnPrediction/
│
├── churn_prediction.ipynb        # Full model implementation in Jupyter Notebook
├── Telco-Customer-Churn.csv      # Dataset used for training and testing
├── requirements.txt              # List of required libraries
├── report/
│   └── Telecom_Churn_Report.docx # Project report for academic submission
├── README.md                     # Project overview and usage guide
```

---

## 📊 Dataset Information

- **Source**: IBM Sample Dataset (via Kaggle)
- **Rows**: 7043 customers
- **Columns**: 21 features including:
  - `gender`, `SeniorCitizen`, `tenure`, `Contract`, `MonthlyCharges`, `Churn`

---

## 🔍 Objectives

- Predict whether a customer will churn or not
- Identify key factors contributing to churn
- Evaluate and compare multiple machine learning models

---

## 🛠️ Tools & Libraries

- Python 3
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn
- scikit-learn

---

## 🤖 Models Implemented

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier (Best Performer)

---

## 📈 Model Results

- **Random Forest** achieved ~82% accuracy
- Top influential features: `Contract`, `tenure`, `MonthlyCharges`
- Evaluation metrics: accuracy, precision, recall, F1-score, ROC-AUC

---

## 🚀 How to Run

1. Clone this repository:
   ```
   git clone https://github.com/your-username/CustomerChurnPrediction.git
   ```

2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Open the notebook:
   ```
   jupyter notebook churn_prediction.ipynb
   ```

---

## 📌 Future Improvements

- Add hyperparameter tuning (GridSearchCV)
- Try XGBoost or LightGBM
- Deploy the model using Flask or Streamlit

---

## 📃 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

[Your Name] • [Your College] • 2025

