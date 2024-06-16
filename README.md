# CARDIOVASCULAR-DISEASE-PREDICTION

This repository contains code and resources for predicting cardiovascular disease using advanced analytics techniques on extensive healthcare data. We utilized Google Cloud Platform (GCP) services such as BigQuery for data ingestion and real-time querying, and Apache Spark for distributed processing. The random forest (RF) algorithm was employed for classification, achieving an accuracy of 84.56%.

# Contents
1. Data Ingestion: Instructions on how to ingest healthcare data into Google BigQuery for further processing.
2. Preprocessing: Details on preprocessing steps applied to the data to prepare it for model training.
3. Model Training: Code and resources related to training the random forest (RF) model using Apache Spark.
4. Evaluation: Evaluation metrics and results of the trained model.
5. Deployment: Instructions on deploying the trained model for real-time prediction.
6. Dependencies: List of dependencies required to run the code.
7. References: Links to relevant papers, articles, and documentation.

# Data Ingestion
To ingest healthcare data into Google BigQuery, follow these steps:

1. Create a Google Cloud Platform (GCP) project.
2. Set up a BigQuery dataset to store the healthcare data.
3. Use Google Cloud Storage (GCS) to upload the healthcare data in a suitable format (e.g., CSV).
4. Use BigQuery's data transfer service or load the data directly from GCS into BigQuery tables.

# Preprocessing
Before training the model, preprocess the data to handle missing values, normalize features, and encode categorical variables. This ensures that the data is suitable for training the random forest model.

# Model Training
The model training phase involves using Apache Spark for distributed processing. The code provided in this repository demonstrates how to train a random forest (RF) model using Spark's MLlib library. Adjust the hyperparameters as necessary based on the dataset and performance requirements.

# Evaluation
After training the model, evaluate its performance using appropriate metrics such as accuracy, precision, recall, and F1-score. The evaluation results are crucial for assessing the model's effectiveness in predicting cardiovascular disease.

# Deployment
To deploy the trained model for real-time prediction, consider using Google Cloud AI Platform or similar services. Provide instructions on how to deploy the model and make predictions using the deployed endpoint.

# Dependencies
Ensure you have the following dependencies installed:

Apache Spark
Google Cloud SDK
Python libraries: pandas, scikit-learn, pyspark

# References
[Google BigQuery Documentation](https://cloud.google.com/bigquery)


[Apache Spark Documentation](https://spark.apache.org/docs/latest/)




 
 Happy coding!

