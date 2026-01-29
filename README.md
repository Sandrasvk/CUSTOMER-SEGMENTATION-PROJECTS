# Customer Segmentation Analysis Portfolio 🚀

## 📌 Project Overview
This repository contains two machine learning projects that use *Unsupervised Learning* to solve real-world problems. By grouping customers using K-Means clustering, I identified hidden patterns in spending and credit behavior to help businesses make better decisions.

## 🏬 Project 1: Mall Customer Segmentation
*Goal:* Group mall shoppers based on their annual income and spending habits.

### 📊 Data & Preprocessing
* *Dataset*: 200 entries with features like Age, Gender, Income, and Spending Score.
* *Cleaning*: Removed CustomerID and checked for null values.
* *Encoding*: Created a custom zeroone(x) function to convert 'Genre' into numbers (Male: 0, Female: 1).
* *Visualization*: Used Seaborn scatter plots to see how customers are spread out.

### 💡 Results
* Segmented customers into *3 distinct clusters*.
* Identified a "Premium" group: High Income + High Spending Score.

## 💳 Project 2: Credit Card Customer Clustering
*Goal:* Categorize bank customers based on their credit limit and the number of cards they own.

### 📊 Data & Preprocessing
* *Key Features*: Avg_Credit_Limit and Total_Credit_Cards.
* *Inspection*: Used .info() and .describe() to understand the data distribution.
* *Modeling*: Used KMeans(n_clusters=4) to find 4 different customer types.

### 💡 Results
* *Cluster 0 & 1*: Moderate to low credit users.
* *Cluster 2 & 3*: High-limit "Premium" users with multiple cards.
* *Visuals*: Created color-coded scatter plots (Red, Green, Blue, Violet) to show the 4 segments.
* 
## 🛠️ Tech Stack
* *Language*: Python
* *Libraries*: Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn
* *IDE*: Jupyter Notebook

## 🚀 How to View
1. Open the .ipynb files directly here on GitHub to see the code and graphs.
2. The datasets used are Mall_Customers.csv and the Credit Card customer data.
