# RFM Customer Segmentation

Customer segmentation using RFM analysis, DBSCAN, and K-Means clustering.

## Overview

This project uses transactional customer data to segment customers based on:

- **Recency**: How recently a customer purchased
- **Frequency**: How often a customer purchased
- **Monetary**: How much a customer spent

RFM features were prepared, scaled, and analyzed to identify meaningful customer groups. :contentReference[oaicite:0]{index=0}

## Approach

- Transaction data cleaning and preprocessing
- RFM feature engineering
- Distribution and skewness analysis
- Feature scaling
- DBSCAN clustering
- k-distance analysis for selecting `eps`
- K-Means clustering
- Cluster visualization and interpretation

## Clustering Analysis

DBSCAN was evaluated across different `eps` values. It produced mostly one large cluster and a small number of noise points, indicating that the dataset did not have suitable density separation for DBSCAN. :contentReference[oaicite:1]{index=1} :contentReference[oaicite:2]{index=2}

K-Means was therefore used as an alternative and produced **four customer segments** using scaled RFM features. :contentReference[oaicite:3]{index=3}

## Business Applications

The resulting segments can support:

- Targeted marketing campaigns
- Customer retention strategies
- Reactivation offers
- Customer value and engagement analysis

The project demonstrates how RFM analysis combined with clustering can support actionable customer segmentation. :contentReference[oaicite:4]{index=4}

## Technologies

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
