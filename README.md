# Intrusion-Detection-System-Project
A robust Machine Learning framework for Network Intrusion Detection using Random Forest algorithms. Designed to classify cyber-attacks and anomalies on the KDD Cup 1999 dataset with high precision, prioritizing system safety and operational continuity.

# 🛡️ Network Intrusion Detection System

### *AI-Driven Security & Anomaly Detection*

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
[![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

## 📋 Executive Summary
This project implements a machine learning-based **Intrusion Detection System (IDS)** designed to classify network traffic as either "normal" or "malicious." 

In safety-critical industries (like aerospace or defense), maintaining the integrity of data pipelines is paramount. This system leverages the **Random Forest** algorithm to detect anomalies with high precision, ensuring operational continuity and "Safety First" compliance.

## 🚀 Key Features
* **High-Fidelity Classification:** Utilizes Random Forest to distinguish between normal traffic and varying attack vectors (DoS, Probe, R2L, U2R).
* **Data-Driven Reliability:** Trained on the benchmark **KDD Cup 1999** dataset.
* **Operational Visibility:** Includes detailed visualizations (Confusion Matrices, Feature Importance) to make model decisions explainable.
* **Robust Preprocessing:** Handles class imbalances and complex feature engineering to minimize false positives.

## 🛠️ Technical Architecture
The pipeline consists of four core stages:
1.  **Data Ingestion:** Loading and cleaning the KDD Cup 1999 dataset.
2.  **Feature Engineering:** Encoding categorical variables and scaling numerical features for model optimization.
3.  **Model Training:** Deploying a **Random Forest Classifier** for robust, ensemble-based learning.
4.  **Evaluation:** Validating performance using Precision, Recall, and F1-Score metrics to ensure "safety-critical" reliability.

## 📊 Performance & Impact
* **Algorithm:** Random Forest Classifier (Chosen for its resistance to overfitting and high accuracy).
* **Impact:** successfully identifies network intrusions, demonstrating how AI can be applied to secure infrastructure—a core competency for industrial data labs.

## 📂 Project Structure
* `Intrusion_Detection_System_Project.ipynb`: The core Jupyter Notebook containing the training logic and analysis.
* `Project_Presentation.pdf`: A high-level overview of the methodology and results.

## 💻 How to Run
You can view and run the code directly in Google Colab:
[**Open in Google Colab**](https://colab.research.google.com/drive/1kxy_ia3RMpAX9klQTEAXJZV53HyEI32s?usp=drive_link)

## 👤 Author
**Sravani Bandela**
* **Role:** Data Scientist & AI Engineer
* **Focus:** GenAI, MLOps, and Industrial AI Safety.
