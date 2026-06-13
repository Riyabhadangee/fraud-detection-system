# 🛡️ Real-Time Fraud Detection System.

[![Python 3.9+](https://img.shields.io/badge/python-3.9+-blue.svg)](https://www.python.org/downloads/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.95+-green.svg)](https://fastapi.tiangolo.com/)
[![Docker](https://img.shields.io/badge/Docker-Ready-blue.svg)](https://www.docker.com/)

> **Designed and developed an end-to-end fraud detection platform using ensemble machine learning models, real-time transaction scoring, explainable AI, and interactive monitoring dashboards.**

---

## 🚀 Key Features

### 🤖 Machine Learning Pipeline
- Ensemble learning using Random Forest, XGBoost, and Logistic Regression
- Real-time fraud prediction through REST APIs
- Feature engineering and preprocessing pipeline for transaction data
- SHAP-based model explainability for transparent decision making
- Class imbalance handling and model performance optimization

### 🔄 Backend & Deployment
- FastAPI-based backend with automatic API documentation
- Streamlit dashboard for fraud analytics and visualization
- Dockerized application for consistent deployment
- Modular and scalable project architecture
- Automated testing and validation workflows

### 📊 Model Performance
- Precision: 94.2%
- Recall: 89.7%
- F1-Score: 91.9%
- ROC-AUC: 0.968

---

## 🏗️ System Architecture

```mermaid
graph TB
    A[Transaction Input] --> B[Data Preprocessing]
    B --> C[Feature Engineering]
    C --> D[Ensemble Model]
    D --> E[Fraud Risk Score]
    E --> F[Dashboard & Reports]

    D --> G[SHAP Explainer]
    G --> H[Prediction Explanation]

    subgraph "Machine Learning Models"
        I[Random Forest]
        J[XGBoost]
        K[Logistic Regression]
    end

    I --> D
    J --> D
    K --> D
