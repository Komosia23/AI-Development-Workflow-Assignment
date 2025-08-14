# AI-Development-Workflow-Assignment
# AI Problem Solving & Case Study Assignment

## Overview
This repository contains the solutions for an AI assignment focused on problem definition, data preprocessing, model development, evaluation, and deployment. The assignment includes both a hypothetical scenario (predicting student dropout rates) and a case study (predicting patient readmission risk within 30 days).

---

## Part 1: Short Answer Questions

### Problem Definition
- **Hypothetical AI Problem:** Predicting student dropout rates in universities.
- **Objectives:**
  1. Identify students at high risk of dropping out early.
  2. Recommend targeted interventions to reduce dropout.
  3. Improve overall student retention rates.
- **Stakeholders:** University administrators, Academic advisors
- **KPI:** Dropout prediction accuracy or reduction in dropout rate.

### Data Collection & Preprocessing
- **Data Sources:** Student academic records, demographics, and engagement data
- **Potential Bias:** Socioeconomic bias may skew predictions
- **Preprocessing Steps:**
  1. Handle missing data
  2. Normalize numeric features
  3. Encode categorical variables

### Model Development
- **Model:** Random Forest
- **Data Split:** 70% training, 15% validation, 15% test
- **Hyperparameters:** Number of trees, Maximum depth of trees

### Evaluation & Deployment
- **Metrics:** Accuracy, F1-Score
- **Concept Drift:** Monitor model performance over time
- **Technical Challenge:** Scalability for large datasets

---

## Part 2: Case Study Application

### Problem Scope
- **Scenario:** Hospital wants to predict patient readmission within 30 days.
- **Objectives:**
  1. Reduce avoidable readmissions
  2. Optimize hospital resource allocation
  3. Early intervention for high-risk patients
- **Stakeholders:** Hospital administrators, Healthcare providers

### Data Strategy
- **Data Sources:** EHRs, Demographics
- **Ethical Concerns:** Patient privacy, Bias against vulnerable populations
- **Preprocessing Pipeline:**
  1. Handle missing values
  2. Feature engineering (comorbidity score, categorical encoding)
  3. Normalize numeric features
  4. Train/validation/test split

### Model Development
- **Model:** Gradient Boosting Classifier
- **Confusion Matrix (Hypothetical):**

|               | Predicted Readmit | Predicted No Readmit |
|---------------|-----------------|-------------------|
| Actual Readmit| 80              | 20                |
| Actual No Readmit | 15          | 185               |

- **Metrics:** Precision ≈ 0.842, Recall = 0.8

### Deployment
- **Integration Steps:**
  1. API endpoint for predictions
  2. Integrate into hospital EHR system
  3. Train staff to interpret predictions
  4. Monitor model performance
- **Compliance:** HIPAA guidelines, data encryption, anonymization

### Optimization
- **Overfitting Solution:** Cross-validation, regularization, early stopping

---

## Repository Structure
