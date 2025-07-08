# Hospital-Readmission-Risk-Predictor


This project predicts the likelihood of a patient being readmitted to the hospital within 30 days after discharge. It uses real hospital records and machine learning models to identify high-risk patients who may need follow-up care.

##  Problem Statement

Develop a predictive model that classifies whether a patient will be readmitted within 30 days of hospital discharge, based on various clinical and demographic attributes.

##  Dataset

- Source: Kaggle Diabetes Readmission Dataset
- Records: 101,766 patient encounters
- Features: 50+ features including demographics, diagnoses, medications, lab tests

###  Files Included

- `HOSPITAL_RISK_PREDICTION.ipynb` – Main Jupyter Notebook with preprocessing, modeling, and evaluation
- `archive (2) (1).zip` – Original dataset
- `README.md` – Project documentation

##  Key Features Used

- Demographics: Race, gender, age
- Hospital stay: Admission type, discharge disposition, time in hospital
- Medical: Diagnosis codes, number of medications, insulin usage, diabetesMed
- Procedures: Lab procedures, outpatient visits, emergency visits

##  Machine Learning Models

- Logistic Regression
- Random Forest
- XGBoost

These models were trained and evaluated to compare performance.

##  Model Evaluation Metrics

- Accuracy
- Confusion Matrix
- ROC-AUC Score
- Precision & Recall

##  Key Challenges Solved

- Handling missing values and unknown codes
- Encoding categorical features
- Managing class imbalance in the readmission target variable
- Feature selection and normalization

## Results

The best-performing model accurately predicted which patients were most likely to be readmitted within 30 days. This can help hospitals prioritize post-discharge follow-ups.

##  Project Structure
Laxmi/
├── HOSPITAL_RISK_PREDICTION.ipynb
├── archive (2) (1).zip
└── README.md 

**Samala Laxmi Prasanna**  
  B.Tech – Artificial Intelligence & Data Science  
  BV Raju Institute of Technology (BVRIT)  
  [GitHub Profile](https://github.com/22211a7254)


