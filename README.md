# 💳 Real-Time Credit Card Fraud Detection System

## 🌟 Project Overview
The Real-Time Credit Card Fraud Detection System is designed to detect fraudulent transactions in real time. Using **Apache Spark** for distributed data processing, **Kafka** for streaming transaction data, and **Cassandra** for scalable data storage, this system processes transactions as they occur. Machine learning models built with **Spark ML** classify transactions, while **Apache Airflow** manages automated workflows for consistent and efficient fraud detection.

## 🚀 Features
- **⚡ Real-Time Data Processing:** Utilizes **Apache Spark** for real-time data analysis and transaction classification.
- **📈 Machine Learning Models:** Implements models for fraud detection, using **StringIndexer** and **VectorAssembler** for data preparation and classification.
- **💾 Scalable Storage:** Integrates **Cassandra** to handle large volumes of transaction data across distributed systems.
- **🔄 Kafka Streaming:** Processes streaming transaction data in real time with **Apache Kafka**.
- **📅 Automated Workflow Management:** **Apache Airflow** schedules and monitors Spark jobs, ensuring reliable and timely fraud detection.

## ⚙️ Tech Stack
- **Distributed Processing:** Apache Spark
- **Streaming Data:** Apache Kafka
- **Database:** Cassandra
- **Workflow Management:** Apache Airflow
- **Languages:** Java, Scala

## 🗂️ Project Structure
The project follows a modular design:
- **src/**: Contains source code, including Spark jobs and machine learning model implementations.
- **config/**: Configuration files for Kafka, Spark, and Cassandra.
- **airflow_dags/**: Defines Airflow DAGs for scheduling and monitoring Spark jobs.
- **models/**: Machine learning models used for fraud detection.
- **scripts/**: Scripts for setting up Kafka topics, Spark jobs, and database integration.

---

Explore the system's features and how it efficiently identifies fraudulent transactions in real time! 🌐🔒
