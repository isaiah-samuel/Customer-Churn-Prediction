# 🧩 Customer Churn Prediction Web App

> **An end-to-end Machine Learning project** that predicts customer churn and provides business insights to help companies retain valuable customers.

---

## 🚀 Project Overview

Customer churn — when customers stop doing business with a company — directly impacts revenue and growth.  
This project demonstrates how data science can predict churn *before* it happens, allowing businesses to take proactive retention measures.

I designed, trained, and deployed a complete **Customer Churn Prediction System** with an interactive web app interface.

---

## 🎯 Objectives

- Build a machine learning model that predicts whether a customer will churn.
- Analyze key factors contributing to churn.
- Deploy the model as an easy-to-use web application for real-time predictions.
- Provide interpretability using SHAP (feature importance visualization).

---

## 🧩 Tech Stack

**Languages & Tools**
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (Modeling & Evaluation)
- SHAP (Explainable AI)
- Streamlit (Web App)
- Git & GitHub (Version Control)
- Jupyter Notebook (Exploratory Analysis)

---

## 📊 Dataset

- **Source:** Customer dataset (synthetic / telecom-style data)
- **Size:** 10,000+ records
- **Key Features:**
  - `CustomerID`, `Gender`, `Age`, `Tenure`, `Balance`, `Products`, `ActiveMember`, etc.
  - `Exited` — Target variable (1 = churned, 0 = retained)

---

## 🔬 Data Science Workflow

| Stage | Description |
|--------|-------------|
| **1. Data Cleaning** | Removed duplicates, handled missing values, corrected data types |
| **2. Exploratory Data Analysis (EDA)** | Visualized churn patterns by gender, tenure, and balance |
| **3. Feature Engineering** | Created categorical encodings, scaled numeric values |
| **4. Model Building** | Tested Logistic Regression, Random Forest, and XGBoost |
| **5. Evaluation** | Used ROC-AUC, precision, recall, and F1-score |
| **6. Explainability** | Applied SHAP to interpret model predictions |
| **7. Deployment** | Deployed the trained model as a Flask/Streamlit web app |

---

## 🧮 Model Performance

| Metric | Score |
|--------|-------|
| Accuracy | **0.84** |
| Precision | **0.82** |
| Recall | **0.79** |
| ROC-AUC | **0.87** |

📈 *Model identifies customers at risk of churn with strong predictive performance.*


# Insights:
Low account balance and short tenure strongly increase churn probability.
 Active members are much less likely to churn.

 Deployment

The app is deployed using Streamlit Localhost.

🔹 Run locally

# 1. Clone the repo
git clone https://github.com/isaiah-samuel/Customer-Churn-Prediction.git
cd Customer-Churn-Prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the app
python app.py

Then open your browser and go to:
http://127.0.0.1:5000/


Business Impact

Enables proactive customer retention by identifying high-risk users.

Helps allocate marketing efforts and incentives efficiently.

Provides explainable AI insights for decision-makers.

Customer-Churn-Prediction/
│
├── app.py                #  app entry point
├── notebook.ipynb        # Exploratory data analysis and model training
├── model.pkl             # Trained model
├── scaler.pkl            # Scaler for input data
├── requirements.txt      # Dependencies
├── data/                 # Raw or processed datasets
└── README.md             # Project documentation

Author

Isaiah Samuel
📧 [isaiahsamuelseth@gmail.com
]
🌐 https://github.com/isaiah-samuel

💼 Data Scientist | Machine Learning Engineer | AI Enthusiast

Future Improvements

Integrate with customer CRM systems for live scoring.

Build real-time dashboards Streamlit.

Add auto-ML pipeline for retraining with new data.