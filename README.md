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

To compare our **supervised** classification model algorithms, we compared their f1_score to see which fit the data. We observed that the tree-based models, in particular the **RandomForest**, are those that obtains the best results.

<img src="https://github.com/Bictole/MLSECU/blob/master/bench.png" alt="Benchmarks_Results">

We also tested **XGBoost**, its results are excellent, with more than 94% of F1_score obtained for a test dataset with 1000 anomalies out of 10 000 network exchanges.