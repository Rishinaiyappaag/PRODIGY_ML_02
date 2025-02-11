# 🛍️ K-Means Customer Segmentation

## 📖 Project Overview
This project applies **K-Means Clustering** to segment customers based on their purchasing behavior using the **Mall Customers Dataset**. The dataset contains customer information, including **Annual Income** and **Spending Score**, which are used to group customers into distinct clusters.

## 📊 Objective
- Group customers based on their shopping behavior.
- Identify patterns in customer spending using **K-Means Clustering**.
- Visualize the results to gain insights into different customer segments.

---

## 📂 Dataset
**Dataset Name**: `Mall_Customers.csv`  
**Source**: Provided during the project.  

### **Dataset Features**
| Column Name            | Description |
|------------------------|-------------|
| CustomerID            | Unique identifier for customers |
| Gender               | Gender of the customer |
| Age                  | Age of the customer |
| Annual Income (k$)   | Customer’s annual income in thousands of dollars |
| Spending Score (1-100) | A score assigned by the mall based on spending patterns |

We primarily use **Annual Income** and **Spending Score** for clustering.

---

## 🚀 Technologies Used
- **Python** 🐍
- **Google Colab** (For running the Jupyter Notebook)
- **Pandas** (For data manipulation)
- **NumPy** (For numerical computations)
- **Matplotlib & Seaborn** (For data visualization)
- **Scikit-Learn** (For K-Means Clustering)

---

## 🔧 Installation & Setup
### **1️⃣ Install Required Libraries**
If you haven’t already installed the necessary libraries, use the following command:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn

---
📌 Key Steps in the Code
1️⃣ Load & Preprocess Data
Read the dataset using pandas.
Select relevant columns (Annual Income & Spending Score).
Standardize data using StandardScaler() to improve clustering performance.
2️⃣ Finding the Optimal Number of Clusters
Uses the Elbow Method to determine the best K value.
Plots the inertia (WCSS) vs. number of clusters.
3️⃣ Apply K-Means Clustering
Train the KMeans model with the optimal number of clusters.
Assign each customer to a cluster.
4️⃣ Visualize the Clusters
Creates a scatter plot using seaborn to show different customer segments.
Clusters are color-coded for easy interpretation.<br>
---
##**📈 Results & Interpretation**
After running the script:

Customers are divided into distinct clusters based on income and spending.
The visualization helps businesses identify high spenders, budget shoppers, and average spenders.