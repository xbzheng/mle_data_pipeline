# Prototyping Flexible, Scalable, Fault-tolerant Machine Learning Engineering Pipelines

This developing project is a prototype to showcase how to build modern Data Engineering pipelines to support or incorporate Machine Learning models in production. It uses some of most popular and modern technologies in the fields of Data Engineering, Machine Learning/Deep Learning, and DevOps Engineering, and deploys it on the AWS cloud environment.

## What is the Functionality of This Data Product?
Real-time, large scale video tracking using MNIST data.

## The Current Vision of System Design:
It contains data pipeline layer and ML pipeline layer. The data pipeline **ingests** the video data, **process** it in real-time, and then **store** cleaned data in a database. The ML pipeline layer takes the cleaned data from the data pipeline layer to perform real-time **model predictions**. Since it mimics the production environment, the ML model is **auto-scalable** based on the in-coming traffic.  

## Schema of Machine Learning Pipeline


## Components of Machine Learning Pipelines

Data Pipeline Layer:
  1. Data Ingestion
  2. Data Processing
  3. Data Store

Machine Learning Layer:
  1. Model Construction
  2. Model Prediction
  3. Model Continuation
  4. Model Auto-scaling

## Future Discussion:

## Contact
Ivan Zheng (ivanxzheng@gmail.com)
