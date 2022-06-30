# Fraud_Detection [![Profile][title-img]][profile]


[title-img]:https://img.shields.io/badge/-Bictole-pink
[profile]:https://github.com/bictole

This repository contains a complete analysis of a financial dataset and the benchmark of different outliers detection algorithm !

This project is about **Machine Learning and Cybersecurity**.

## Dataset

The dataset is not in the repository. It is the [IEEE CIS Fraud Detection contest 2019](https://www.kaggle.com/c/ieee-fraud-detection/data) : the dataset entails user information as well as transaction information, linked together with a TransactionID.

The objective of this notebook is twofold:
• Deploy data analysis for fraud **detection** in a highly incomplete dataset
• Perform **anomaly detection** using **IsolationForest** and **Local Outlier Factor (LOF)** algorithm
and evaluate their complementarity for *unsupervised* anomaly detection

## Analysis

The analysis is made with python on the `Secu&IA - Lab session 1 – anomaly detection.ipynb` notebook. We are going through the whole analysis process, with the **dataset exploration**, the **cleaning**, the **feature engineering**, **statistical analysis**, **visualization** and finally the **machine learning** part.

## Results

The results are not great, and we can deduce multiple reason. The main one would be that we don't have enough data for this kind of algorithms. The **unsupervised** algorithm are not stable to perform well between each other. But we still find a **correlation** between fraud and outliers, so there is something to get from this implementation.