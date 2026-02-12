# Credit-Risk-Prediction-Model
Project Overview

This project involves the development of a Credit Risk Prediction Model for Lauki Finance, a Non-Banking Financial Company (NBFC) in India.

The objective is to build a predictive credit scoring system that classifies loan applicants into:

❌ Poor

⚠️ Average

✅ Good

🌟 Excellent

The scoring system is inspired by industry-standard credit frameworks like CIBIL and is designed to assist loan officers in making data-driven lending decisions.

🎯 Business Objective

Predict probability of loan default

Categorize applicants into credit risk bands

Enable faster and more accurate loan approval decisions

Reduce manual underwriting effort using automation (STP)

🛠️ Tech Stack

Python

Pandas & NumPy

Scikit-learn

Streamlit

Matplotlib / Seaborn

ML Monitoring Tools

Deployment-ready architecture

📂 Project Scope
🚀 Phase 1 – Model Development & Deployment
1️⃣ Model Development

Built predictive ML model using:

Historical loan data

Default indicators

Performed:

Data cleaning

Feature engineering

Model training & evaluation

Explainability analysis

2️⃣ Credit Scorecard Creation

Developed a scoring framework

Categorized predictions into:

Poor

Average

Good

Excellent

3️⃣ Streamlit Web Application

Built interactive UI for loan officers

Inputs include:

Borrower demographics

Loan details

Bureau data (credit utilization, open accounts, etc.)

Outputs:

Default probability

Credit category

Model-based recommendation

🔍 Phase 2 – Monitoring & ML Ops
📊 Performance Monitoring

Continuous tracking of:

Model accuracy

Precision & Recall

Data drift

Prediction distribution

⚙️ Operational Integration

2-month production trial

Implementation of:

Straight Through Processing (STP)

Automated approval for high-confidence predictions

Reduced manual review effort

📈 Key Features

High model explainability (business-friendly interpretation)

Real-time loan risk prediction

Automated credit categorization

Deployment-ready ML pipeline

Monitoring-ready architecture

📊 Model Explainability

To ensure business trust and regulatory alignment:

Feature importance analysis

Probability-based risk segmentation

Interpretable scoring logic

Business-adjustable thresholds

🏗️ Project Architecture
Data Collection → Data Preprocessing → Feature Engineering
        ↓
Model Training → Evaluation → Scorecard Mapping
        ↓
Streamlit UI Deployment
        ↓
Monitoring & STP Automation

📅 Timeline

Phase 1: 2 Months

Phase 2: Based on learnings from Phase 1 production trial

💰 Estimated Budget (Phase 1)

$18,000 per month

Maximum budget: $36,000

Based on 2 full-time ML resources

👥 Stakeholders
🔹 AtliQ AI

Data Scientist

Data Science Team Lead

Product Owner

🔹 Lauki Finance

Project Sponsor

Client Point of Contact

🚀 How to Run the Project
1️⃣ Clone the Repository
git clone https://github.com/your-username/credit-risk-model.git
cd credit-risk-model

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Run Streamlit App
streamlit run app.py

📌 Future Enhancements

Advanced feature selection

Ensemble modeling

Automated retraining pipeline

Real-time data drift detection

Cloud deployment (AWS / Azure / GCP)
