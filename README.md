# Clustering: Decoding Customer Segments

## Context
In today's digital era, understanding and segmenting customer banking behavior is crucial for banks to deliver personalized services and predict customer needs effectively. *Clustering: Decoding Customer Segments* leverages advanced data analysis techniques to segment customers and identify trends, helping banks adapt to diverse customer preferences and behaviors.

## Dataset
The dataset used in this project includes over 1 million transactions from more than 800,000 customers of a bank in India. The key features of the dataset are:

- *TransactionID*: Unique identifier for each transaction.
- *CustomerID*: Unique identifier for each customer.
- *CustomerDOB*: Date of Birth of the customer.
- *CustGender*: Gender of the customer.
- *CustLocation*: Location of the customer.
- *CustAccountBalance*: Account balance at the time of the transaction.
- *TransactionDate*: Date of the transaction.
- *TransactionTime*: Time of the transaction.
- *TransactionAmount (INR)*: Amount of the transaction in Indian Rupees.

## Project Overview
This project aims to segment bank customers based on their transaction behavior and demographic data, using a variety of clustering techniques. Additionally, it includes anomaly detection to identify unusual transaction patterns that could indicate potential fraud or outliers.

### Key Steps:

1. *Data Preprocessing*:
   - Handling missing values and transforming data.
   - Feature engineering to derive useful insights from raw data.

2. *Customer Segmentation*:
   - *K-Means Clustering*: Applied to segment customers into distinct groups based on their transaction behaviors and demographics.
   - *Hierarchical Clustering*: Used to further validate and explore the customer segments.
   - *DBSCAN (Density-Based Spatial Clustering of Applications with Noise)*: Captures clusters based on density, identifying non-linear shapes and noisy data points.
   - *Spectral Clustering*: Utilizes graph theory to find clusters in complex, non-convex datasets.

3. *Anomaly Detection*:
   - *Isolation Forest*: Identifies unusual transactions that deviate from typical customer behavior.
