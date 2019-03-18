
# Capstone Project: Create a Customer Segmentation Report for Arvato Financial Services
Udacity Data Scientist Nanodegree capstone project to create Customer Segmentation for Arvato Financial Services

## Table of Contents

- [Project Overview](#projectoverview)
- [Technical Overview](#technicaloverview)
- [Requirements](#requirements)



***

<a id='projectoverview'></a>

## 1. Project Overview

In this project, we are provided with demographic data of customers of a mail-order company in Germany and demographic data of general population of Germany. Using this data, we are required to identify new customers for the company.

We approach this project in 2 phases:
* Use Unsupervised Learning to perform customer segmentation and identify clusters/segments from general population who best match mail-order company's customer base.
* Use Supervised Learning to identify targets for marketing campaign of the mail-order company who could possibly become their customers.

Goal of this project is to predict individuals who are most likely to become customers for a mail-order sales company in Germany.

Please find detailed overview of the project in blog post: https://medium.com/@venkateshrajagopalan86/customer-segmentation-for-arvato-financial-services-42ac87870b3c

<a id='technicaloverview'></a>

## 2. Technical overview:

Step by step workflow from data exploration, processing to inference is approached in a structured fashion. Because of the large volume of source data, we build preprocessing pipeline  to get rid of unnecessary and outlier data and implement Dimensionality Reduction and Clustering to identify segments. Due to the nature of the data (details in notebook), AUC/ROC is used as the evaluation metric for this project. Prediction for test set is to be submitted to Kaggle competition for evaluation.

Following concepts implemented and covered in detail in the notebook: 
* Data Exploration & Cleansing
* Dimensionality Reduction
* Clustering
* Supervised Learning
* Final Model Evaluation
* Feature Importance
* Analysis of identified important features in clusters to find relevance
* Scoring and submisstion to Kaggle


## 3. Requirements

All of the requirements are captured in requirements.txt. 
Run: pip install -r requirements.txt



