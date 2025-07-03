# 🧪 End-to-End MLOps Project with MLflow, Docker, and CI/CD

A full-stack Machine Learning project that automates the entire ML lifecycle — from data ingestion to model deployment — using modular Python code, MLflow for experiment tracking, Docker for containerization, and GitHub Actions for CI/CD.

![image](https://github.com/user-attachments/assets/250f48eb-aab7-4483-9e7b-fe4303dfbf88)


> 🎯 Built using ElasticNet regression on wine quality data. Designed for real-world ML engineering with automated workflows and production-grade architecture.

---

## 🚀 Project Highlights

- 🧱 **Modular Project Structure** with reusable components and YAML-based configuration
- 🧪 **ML Pipeline**: Ingestion → Validation → Transformation → Training → Evaluation
- 📊 **MLflow Integration** for experiment logging, hyperparameter tuning, and visual analysis
- 🐍 **Python Templates** automate directory structure and boilerplate setup
- 🐳 **Dockerized Deployment** for portability and reproducibility
- 🌐 **Flask Web App** for user-triggered model training and predictions

---

## 📊 ML Pipeline

### ✅ Stages Implemented
| Stage              | Description |
|-------------------|-------------|
| **Data Ingestion**     | Downloads zipped dataset, unpacks, and saves locally |
| **Data Validation**    | Validates schema and structure before proceeding |
| **Data Transformation**| Splits, scales, and stores train/test sets |
| **Model Training**     | Trains ElasticNet model with hyperparameters from YAML |
| **Model Evaluation**   | Logs RMSE, MAE, R², and parameters to MLflow |

---

## 🔍 MLflow Experiment Tracking

- Logs parameters, metrics, artifacts
- Enables version control for experiments
- Interactive UI to compare runs and tune models
- Supports remote tracking via **DagsHub**

---

## ⚙️ Deployment Stack Understanding

| Tool         | Purpose |
|--------------|---------|
| **Docker**        | Build and ship app as container |
| **AWS EC2**       | Host the production Flask app |
| **AWS ECR**       | Container registry for images |
| **GitHub Actions**| CI/CD pipeline to automate push → build → deploy |
| **Self-hosted Runner** | GitHub runner on EC2 to auto-deploy |

---

## 📦 Flask Web Interface

- 🌐 Built using Flask + Bootstrap  
- 🧪 Routes for: home, train model, make prediction  
- 🧠 Accepts user input and returns predicted wine quality  

---

## 🔁 CI/CD Pipeline Overview

### ✅ GitHub Actions Workflow
- **CI**: Linting, test hooks (sample stubbed)
- **CD**: Push Docker image to AWS ECR
- **Deploy**: Pull image on EC2 and run container

🧠 Key Concepts Demonstrated

    ✅ Production-ready ML system design

    ✅ Cloud-native deployment using DevOps principles

    ✅ MLflow for version-controlled experiment tracking

    ✅ Containerization and reproducibility via Docker

> 📚 This project is a guided implementation for learning MLOps and production-ready ML workflows. It has been adapted and customized to reinforce core concepts in experiment tracking, containerization, CI/CD, and understand cloud deployment.
> Complete code is maintained in a private repo
