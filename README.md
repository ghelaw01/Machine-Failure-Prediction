# Machine-Failure-Prediction

Predictive Maintenance - End-to-End Machine Learning Pipeline (R)
  Project Overview
Predictive maintenance uses machine learning on sensor data to predict failures before they happen, reducing downtime and costs. This project builds an end-to-end pipeline using R, XGBoost, Plumber (API), and Docker.

  Features
✔ Data Preprocessing & Feature Engineering
✔ Machine Learning Model (XGBoost)
✔ REST API Deployment (Plumber)
✔ Model Monitoring (MLflow)
✔ Containerization (Docker)

Project Structure

📁 predictive-maintenance-ml-r
│── 📂 data (Raw & Processed Sensor Data)
│── 📂 notebooks (Exploratory Data Analysis)
│── 📂 src (Data Processing & Model Training)
│── 📂 deployment (Plumber API)
│── 📂 monitoring (MLflow Setup)
│── 📜 README.md (Project Overview)
│── 📜 requirements.R (Dependencies)
│── 📜 docker-compose.yml (Docker Setup)

Install Dependencies

install.packages(c("xgboost", "plumber", "data.table", "jsonlite", "caret"))

Dataset
timestamp	                  sensor_1	                             sensor_2	                        sensor_3	                           machine_failure
2024-03-01 12:00:00	            0.5	                                 0.6	                             0.7	                                      0
2024-03-01 12:01:00	            0.8	                                 0.5	                             0.6	                                      1
Source: NASA CMAPSS Dataset

📞 Contact
📧 Email: ghelaw01@gmail.com
💼 LinkedIn: https://www.linkedin.com/in/zemenghelaw





