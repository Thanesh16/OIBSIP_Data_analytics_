# Customer Personality Analysis & Segmentation — Project 02

## 📌 Project Overview
This project focuses on **Customer Personality Analysis** to help a business understand its customers' behaviors. By performing Exploratory Data Analysis (EDA) and Data Cleaning, the goal is to segment customers based on their spending patterns and demographics to optimize marketing strategies.

## 📊 Project Summary
| Feature | Details |
| :--- | :--- |
| **Dataset** | `ifood_df.csv` (2,205 entries) |
| **Objective** | Market Segmentation & Behavioral Analysis |
| **Main Tools** | Python (Pandas, Seaborn, Scikit-learn) |
| **Key Algorithm** | K-Means Clustering (Silhouette Analysis) |

## 🚀 Analysis Workflow
1. **Data Cleaning:** Removed non-informative columns (`Z_CostContact`, `Z_Revenue`) and verified zero null values.
2. **Outlier Treatment:** Applied the Interquartile Range (IQR) method to remove anomalies in `Income` and `MntTotal`.
3. **EDA:** visualized income distributions and spending correlations across product categories (Wines, Meat, etc.).
4. **Segmentation:** Calculated **Silhouette Scores** for $K$ ranges (2–10) to determine the most distinct customer groups.

## 🛠️ Tech Stack
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `sklearn.metrics` (Silhouette Score), `sklearn.cluster` (K-Means)

## 📂 Project Structure
* `Project 02.ipynb` - Step-by-step cleaning, EDA, and clustering logic.
* `ifood_df.csv` - The customer marketing dataset.

---
*Developed as part of an Internship project.*
