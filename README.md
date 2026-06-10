# 📊 Customer Churn Prediction & Explainable AI Dashboard

A Streamlit-based machine learning application that predicts customer churn and provides explainable insights using SHAP (SHapley Additive Explanations).

## 🚀 Features

- Single Customer Churn Prediction
- Bulk Prediction via CSV Upload
- Explainable AI (SHAP)
- Analytics Dashboard
- Prediction History
- AI Assistant
- Modern Dark-Themed Interface

## 🛠️ Technologies Used

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- SHAP
- Plotly
- SQLite

## 📂 Project Structure

```text
app.py
database.py
theme.py
churn_model.pkl
feature_columns.pkl
model_metadata.json
telco_churn.csv
requirements.txt
views/
images/
```

## ▶️ Installation

```bash
git clone https://github.com/dhanushree-codes/churn-prediction.git
cd churn-prediction
pip install -r requirements.txt
streamlit run app.py
```

## 🧠 Model Details

- Algorithm: Random Forest Classifier
- Features: Customer demographics, billing information, and service usage
- Performance: ROC-AUC ≈ 83%

## 🔍 Explainable AI

This project integrates SHAP to:

- Explain individual predictions
- Identify churn-driving factors
- Visualize feature importance
- Improve model transparency

## 📈 Future Enhancements

- Real-time API deployment
- Enhanced SHAP visualizations
- Customer segmentation
- Model retraining pipeline

## 👩‍💻 Author

**Dhanushree HP**

GitHub: https://github.com/dhanushree-codes
