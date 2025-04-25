# Flight-Cancellations-Prediction-Using-PySpark

Predicting flight cancellations using Big Data technologies and Machine Learning for proactive airline management.

# Project Overview

Flight cancellations cause major disruptions for travelers and financial losses for airlines. This project leverages PySpark and Support Vector Machine (SVM) algorithms within a Hadoop cluster to predict potential flight cancellations. By utilizing distributed computing, we efficiently process millions of flight records to deliver a scalable, high-performance predictive model suitable for real-time airline operations.

# Tech Stack

Big Data Framework: Hadoop 3.3.6 (3-node cluster)
Distributed Computing: Apache Spark
Machine Learning: PySpark MLlib (SVM)
Programming Language: Python 3.12.7
Cluster Setup: 1 Master Node (Windows 11) & 2 Worker Nodes (macOS Sequoia)
Jupyter Notebook: For development and experimentation

# Dataset

Source: Kaggle - Flight Cancellations Dataset
Features: Flight Number, Airline, Departure Time, Arrival Time, Delay, Cancellation Reason, etc.
Preprocessing:
Handling missing values
Feature selection & normalization
Encoding categorical variables

# How It Works

**Data Loading & Preprocessing:**

Load historical flight data into the Hadoop cluster.

Clean, transform, and prepare data for modeling.

**Model Training:**

Apply SVM classifier using PySpark.

Split data into training and testing sets.

**Distributed Processing:**

Leverage Hadoop's parallel processing to handle large-scale data efficiently.

Resource management via YARN and monitoring through Spark Master Dashboard.

**Model Evaluation:**

Metrics used: Accuracy, Precision, Recall, F1-Score.

Achieved 98% accuracy with strong precision and recall balance.

# Results

Accuracy: 98%

Precision: 0.98

Recall: 1.00

The model effectively predicts flight cancellations, enabling proactive decision-making for airlines.

# Big Data Characteristics Addressed

Volume: Processed millions of flight records.

Veracity: Cleaned and reliable dataset.

Value: Helps optimize airline operations.

Variability: Adaptable to changing flight patterns.

Visualization: Clear insights into cancellation trends and model performance.

# Installation & Setup

Clone the Repository

git clone https://github.com/KarthiksharanBalasubramanian/flight-cancellation-prediction.git

cd flight-cancellation-prediction

Set Up Hadoop & Spark Cluster

Configure a 3-node Hadoop cluster.

Install Apache Spark on all nodes.

Install Python Libraries

pip install pyspark pandas numpy

Run the Notebook Launch Jupyter Notebook and execute Big_Data_Project.ipynb.

# Future Enhancements

Explore other ML models (e.g., Decision Trees, Neural Networks).

Integrate real-time data streaming.

Implement advanced optimization techniques for faster predictions.

# Acknowledgements

Thanks to Dr. Abedalrhman Alkhateeb for guidance and support throughout this project.

