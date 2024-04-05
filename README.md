# Customer-Segmentation for Targeted Marketing Campaign

This repository contains code for clustering customers based on their attributes using Principal Component Analysis (PCA).

**Overview**
Customer clustering is a common technique used in marketing and customer relationship management to segment customers into distinct groups based on their similarities. This project aims to cluster customers using PCA, a dimensionality reduction technique, to identify underlying patterns in the customer data.

Features
Perform dimensionality reduction using PCA to extract important features from customer data.
Utilize clustering algorithms to group customers based on their extracted features.
Visualize customer clusters and explore insights from the clustering results.

**Prepare Customer Data:** 
Obtain customer data in a suitable format (e.g., CSV, Excel) and preprocess it as necessary for clustering.

**Usage**
Data Preprocessing: Perform data cleaning and preprocessing steps, including handling missing values and scaling features if necessary.
Dimensionality Reduction: Apply PCA to reduce the dimensionality of the customer data while retaining important information.
Clustering: Apply clustering algorithms (e.g., K-means, DBSCAN) to the PCA-transformed data to group customers into clusters.
Visualization and Analysis: Visualize customer clusters using appropriate plots and charts (e.g., scatter plots, dendrograms). Analyze and interpret the clustering results to gain insights into customer segmentation.

**Dataset**
Sure, here's a summarized description of the attributes in the dataset:

cust_id: Categorical identifier for the credit card holder.
balance: Total amount owed to the credit card company.
balance_frequency: Frequency of balance updates, scored between 0 and 1 (1 = frequently updated, 0 = not frequently updated).
purchases: Total amount of purchases made from the account.
oneoff_purchases: Maximum purchase amount done in a single transaction.
installments_purchases: Amount of purchases made in installments.
cash_advance: Cash advances given by the user.
purchases_frequency: Frequency of purchases, scored between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased).
oneoff_purchases_frequency: Frequency of one-off purchases, scored between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased).
purchases_installments_frequency: Frequency of purchases in installments, scored between 0 and 1 (1 = frequently done, 0 = not frequently done).
cash_advance_frequency: Frequency of cash advances being paid.
cash_advance_trx: Number of transactions made with cash advances.
purchases_trx: Number of purchase transactions made.
credit_limit: Credit card limit for the user.
payments: Amount of payments made by the user.
minimum_payments: Minimum amount of payments made by the user.
prc_full_payment: Percent of full payment paid by the user.
tenure: Tenure of credit card service for the user in years.+

_Link_
https://www.kaggle.com/code/zohrenotash/customer-clustring-using-pca/input


**Acknowledgments**
Thank ZOHRE NOTASH (Kaggle) for resources. 
