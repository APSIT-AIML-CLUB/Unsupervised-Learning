# 📚 HOMEWORK ASSIGNMENT - Unsupervised Learning

A new dataset to practice your newly gained clustering skills on!

## 📌 Overview

This project is an assignment to apply **K-Means clustering** on the Wholesale Customers Dataset.  
The goal is to explore patterns in customer purchasing behavior and segment them into distinct groups based on their annual spending in various product categories.

## 📂 Dataset

- The dataset contains annual spending amounts for customers of a wholesale distributor, along with categorical indicators for their **business type** and **geographical region**.

- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/292/wholesale+customers)

### Columns

| Column               | Description                                                              |
| -------------------- | ------------------------------------------------------------------------ |
| **Channel**          | Type of customer: `1` = Horeca (Hotel/Restaurant/Café), `2` = Retail     |
| **Region**           | Geographical region: `1` = Lisbon, `2` = Oporto, `3` = Other             |
| **Fresh**            | Annual spending on fresh products (fruits, vegetables, meat, fish, etc.) |
| **Milk**             | Annual spending on milk and milk-based products                          |
| **Grocery**          | Annual spending on grocery items (non-perishable food, dry goods, etc.)  |
| **Frozen**           | Annual spending on frozen products                                       |
| **Detergents_Paper** | Annual spending on detergents and paper products                         |
| **Delicatessen**     | Annual spending on delicatessen (gourmet foods, specialty items)         |

## 🎯 Task

- Preprocess the dataset (handle scaling, check for outliers, etc.)
- Apply **K-Means clustering** to group customers based on purchasing patterns
- Analyze the resulting clusters
- Visualize the clusters using appropriate techniques (e.g., PCA for dimensionality reduction)
