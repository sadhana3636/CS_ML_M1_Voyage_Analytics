
# 🌍 Travel & Tourism ML Capstone Project : Voyage_Analytics
# Productionization of ML Systems

## 📊 Business Context

In the travel and tourism industry, data-driven decision-making can significantly enhance user experience and operational efficiency. This project leverages **data analytics and machine learning** to improve how travel services—such as flights and hotels—are analyzed, predicted, and recommended.

The project integrates three core datasets:

* **Users**
* **Flights**
* **Hotels**

Each dataset provides insights into customer behavior, travel patterns, and pricing dynamics. The goal is to build scalable ML systems while implementing **end-to-end MLOps practices**.

---
## 🏗️ Project Workflow

Data → Preprocessing → Model Training → API Deployment → Docker → Kubernetes → CI/CD → Monitoring

---

## 📁 Dataset Overview

### 👤 Users Dataset

* `code`: User ID
* `company`: Associated company
* `name`: User name
* `gender`: Gender
* `age`: Age

---

### ✈️ Flights Dataset

* `travelCode`: Travel ID
* `userCode`: Linked user ID
* `from`: Origin
* `to`: Destination
* `flightType`: Class type
* `price`: Ticket price
* `time`: Duration
* `distance`: Distance
* `agency`: Booking agency
* `date`: Travel date

---

### 🏨 Hotels Dataset

* `travelCode`: Travel ID
* `userCode`: Linked user ID
* `name`: Hotel name
* `place`: Location
* `days`: Stay duration
* `price`: Price per day
* `total`: Total cost
* `date`: Booking date

---

## 🎯 Project Objectives

### 🔹 1. Flight Price Prediction (Regression)

* Built a regression model to predict flight prices
* Performed feature engineering, model training, and validation
* Focused on improving prediction accuracy

---

### 🔹 2. REST API Development

* Developed a **Flask-based API**
* Enabled real-time flight price predictions

---

### 🔹 3. Containerization (Docker)

* Packaged the model using Docker
* Ensured portability and reproducibility

---

### 🔹 4. Scalability with Kubernetes

* Deployed model using Kubernetes
* Handled scaling and load management

---

### 🔹 5. Workflow Automation (Apache Airflow)

* Designed DAGs for data pipelines
* Automated model workflows

---

### 🔹 6. CI/CD Pipeline (Jenkins)

* Implemented automated build & deployment
* Ensured continuous integration

---

### 🔹 7. Model Tracking (MLflow)

* Tracked experiments and model versions
* Enabled reproducible ML workflows

---

### 🔹 8. Gender Classification Model

* Built a classification model using **BERT**
* Predicted gender from names

---

### 🔹 9. Hotel Recommendation System

* Developed a hybrid recommendation system
* Combined **Collaborative + Content-Based Filtering**
* Built an interactive **Streamlit dashboard**

---

## 💼 Business Impact

* 📈 Improved decision-making for travel pricing
* 🎯 Personalized hotel recommendations
* ⚡ Real-time prediction systems via APIs
* 🔄 Automated and scalable ML pipelines
* 🚀 Production-ready ML deployment

---

## 🧠 Skills Demonstrated

* Machine Learning (Regression, Classification, Recommendation Systems)
* NLP (BERT)
* MLOps (Docker, Kubernetes, Jenkins, Airflow, MLflow)
* API Development (Flask)
* Data Processing & Feature Engineering
* Data Visualization (Streamlit)


