# Customer Churn Prediction

A Streamlit machine learning app that predicts customer churn, supports single and bulk predictions, shows analytics dashboards, tracks prediction history, and provides model insights.

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

## Project Structure

churn_project/
├── app.py
├── database.py
├── theme.py
├── requirements.txt
├── churn_model.pkl
├── feature_columns.pkl
├── model_metadata.json
├── telco_churn.csv
└── views/

## Usage

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

 ## Model

The app uses a trained Random Forest model on the Telco Customer Churn dataset.
Model: Random Forest Classifier
ROC-AUC: ~83%
Features: 11 customer attributes

Author

Developed by Dhanushree
GitHub: dhanushree-codes
```

