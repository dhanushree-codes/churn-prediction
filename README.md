# Customer Churn Prediction

A Streamlit-based machine learning application that predicts customer churn, supports single and bulk predictions, provides explainable AI insights using SHAP, delivers personalized customer retention strategies, visualizes analytics dashboards, tracks prediction history, and offers model insights for data-driven decision-making.


## Features

- Single customer churn prediction
- Bulk CSV prediction
- Analytics dashboard
- Prediction history
- Model insights with ROC-AUC and feature importance
- Explainable AI style feature impact chart
- AI assistant for churn-related questions
- Dark themed Streamlit UI

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Scikit-learn
- Joblib
- Matplotlib
- SQLite

## Installation

```bash
git clone https://github.com/dhanushree-codes/churn-prediction.git
cd churn-prediction/churn_project
pip install -r requirements.txt
streamlit run app.py
```

## Project Structure

```text
churn_project/
├── app.py
├── database.py
├── theme.py
├── requirements.txt
├── churn_model.pkl
├── feature_columns.pkl
├── model_metadata.json
├── telco_churn.csv
├── views/
├── images/
└── README.md
```
## Usage
```bash
Run the app and open:
http://localhost:8501
Use the sidebar to access:
Single Prediction
Bulk Prediction
Analytics Dashboard
Model Insights
Prediction History
AI Assistant
Explainable AI
```

 ## Model

The app uses a trained Random Forest model on the Telco Customer Churn dataset.
Model: Random Forest Classifier
ROC-AUC: ~83%
Features: 11 customer attributes

## Author

Developed by Dhanushree
GitHub: dhanushree-codes
```

