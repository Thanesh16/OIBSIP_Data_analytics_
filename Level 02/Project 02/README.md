# Wine Quality Prediction — Project 02

## 📌 Project Overview
This project focuses on predicting the quality of wine based on its physicochemical properties. By implementing various machine learning classification models, the project identifies key factors such as alcohol content, volatile acidity, and sulphates that determine the sensory quality of wine.

## 📊 Project Summary
| Feature | Details |
| :--- | :--- |
| **Dataset** | `wineQT.csv` |
| **Objective** | Classification of Wine Quality (Good/Bad) |
| **Main Tools** | Python (Pandas, Scikit-learn, Seaborn) |
| **Best Model** | Random Forest Classifier |

## 🚀 Analysis Workflow
1. **Data Preprocessing:** * Checked for null values and performed exploratory data analysis (EDA).
    * Categorized wine quality into a binary classification: 'Good' (7 or higher) and 'Bad' (below 7).
    * Applied **StandardScaler** to normalize the feature set for better model performance.
2. **Data Visualization:** Used bar plots and box plots to visualize the correlation between fixed acidity, citric acid, and residual sugar against wine quality.
3. **Model Implementation:** Implemented and compared three distinct classification algorithms:
    * **Random Forest Classifier**
    * **Stochastic Gradient Descent (SGD) Classifier**
    * **Support Vector Classifier (SVC)**
4. **Evaluation:** Utilized **Confusion Matrices** and **Classification Reports** (Precision, Recall, F1-Score) to measure the accuracy of each model.
5. **Feature Importance:** Identified that `alcohol`, `volatile acidity`, and `sulphates` are the most significant predictors of quality.

## 🛠️ Tech Stack
* **Data Handling:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `sklearn` (RandomForest, SGD, SVC, StandardScaler)

## 📂 Project Structure
* `Project 02.ipynb` - The complete machine learning pipeline from EDA to model comparison.
* `wineQT.csv` - The dataset containing chemical properties of red wine variants.

---
*Developed as part of an Internship project.*
