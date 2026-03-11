# Credit Card Fraud Detection — Project 03

## 📌 Project Overview
This project addresses the challenge of detecting fraudulent credit card transactions. Since fraud cases are significantly fewer than legitimate ones, the project utilizes **SMOTE (Synthetic Minority Over-sampling Technique)** to balance the dataset before training a **Random Forest Classifier**. This ensures the model effectively identifies suspicious patterns without being biased toward normal transactions.

## 📊 Project Summary
| Feature | Details |
| :--- | :--- |
| **Dataset** | `creditcard.csv` |
| **Objective** | Binary Classification (Fraud vs. Genuine) |
| **Main Tools** | Python (Scikit-learn, Imbalanced-learn) |
| **Key Technique** | SMOTE for Class Imbalance Handling |

## 🚀 Analysis Workflow
1. **Data Preprocessing:** * Analyzed the distribution of the `Class` column (0 for Genuine, 1 for Fraud).
   * Applied **StandardScaler** to the `Amount` and `Time` features to bring them to a consistent scale.
2. **Handling Imbalance:** Used **SMOTE** to oversample the minority class (Fraud), ensuring the model learns the characteristics of fraudulent transactions properly.
3. **Model Training:** Implemented a **Random Forest Classifier**, known for its robustness in handling high-dimensional data and complex relationships.
4. **Evaluation:** * Generated a **Confusion Matrix** to track True Positives and False Negatives.
   * Analyzed the **Classification Report** (Precision, Recall, and F1-Score) to ensure high detection rates for fraud.

## 🛠️ Tech Stack
* **Data Handling:** `pandas`, `numpy`
* **Machine Learning:** `sklearn` (RandomForest, StandardScaler), `imblearn` (SMOTE)
* **Visualization:** `matplotlib`, `seaborn`

## 📂 Project Structure
* `Project 03.ipynb` - The full notebook containing data balancing and model training.
* `creditcard.csv` - The dataset containing transaction details (V1-V28 PCA components).

---
*Developed as part of an Internship project.*
