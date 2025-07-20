# Healthcare-Resource-Optimization-Risk-Prediction
This project leverages a simulated hospital management system dataset to build a full-stack data pipeline and perform advanced analytics using Python, MySQL, Looker Studio, and ML techniques. We also incorporate Operations Research (OR) concepts for resource optimization.

## Project Overview
Hospitals often face challenges in managing resources efficiently while providing high-quality care. This project focuses on two major goals:

1. Creating dimensions and facts during ETL process in order to be used further for visualizations.
2. **Predicting High-Risk Patients** using machine learning algorithms for early intervention and better planning. (High risk patients are those who their paiement fails or don't show
up for their appointements)

We use a **structured multi-table dataset** simulating a hospital system with patients, doctors, appointments, treatments, and billing information. This dataset allows for realistic EDA, SQL modeling, ETL pipelines, ML prediction, and data visualization.


## Project Objectives

- Perform **Exploratory Data Analysis (EDA)** to identify patterns in patient visits, treatment types, and billing trends.
- Clean, process, and integrate data using **Pandas** and store it in **MySQL** for advanced querying.
- Build an **ETL pipeline** that can be reused and extended.
- Apply **Operations Research (OR)** to optimize appointment scheduling or doctor-patient assignment.
- Train and evaluate multiple **Machine Learning models** to:
  - Predict **no-shows or cancellations**
  - Identify **high-risk or high-cost patients**
- Create **dashboards** with **Looker Studio** for interactive reporting on KPIs such as:
  - Doctor utilization
  - Appointment trends
  - Billing performance

## Dataset Structure
The dataset includes the following tables:

| File | Description |
|------|-------------|
| `patients.csv` | Patient demographics and insurance info |
| `doctors.csv` | Doctor details and specializations |
| `appointments.csv` | Visit data including status and reasons |
| `treatments.csv` | Type, description, and cost of medical treatments |
| `billing.csv` | Billing details including status and method |


## Tech Stack

| Tool | Use |
|------|-----|
| **Python (Colab)** | Data cleaning, EDA, ML, OR modeling |
| **MySQL** | Relational data storage, fact-dimension modeling |
| **Looker Studio** | Dashboarding and reporting |
| **Pandas & NumPy** | Data wrangling |
| **Scikit-learn, XGBoost** | Machine Learning algorithms |
| **PuLP / OR-Tools** | Operations Research optimization |
| **Matplotlib & Seaborn** | Visual EDA |

## Machine Learning Scope
We will train and compare the following models for risk prediction:

- Logistic Regression
- Random Forest
- ANN
- K-Nearest Neighbors (KNN)

## Expected Deliverables
- Clean and structured MySQL database with relationships
- Looker dashboard with hospital KPIs
- ML models deployed in Colab for patient risk classification
- Optimization model to reduce wait times or costs
- GitHub-hosted source code with documentation

## Contact
Project by **Yessin Jribi**  
For inquiries or collaboration: yessinjribi7@gmail.com
