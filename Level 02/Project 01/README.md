# Housing Price Prediction & Linear Regression — Project 01

## 📌 Project Overview
This project involves building a predictive model to estimate housing prices based on various property features. By performing thorough Data Cleaning, Feature Engineering, and Linear Regression, the project identifies the most significant drivers of real estate value, such as area, bathrooms, and air conditioning.

## 📊 Project Summary
| Feature | Details |
| :--- | :--- |
| **Dataset** | `Housing.csv` |
| **Objective** | Predictive Modeling using Multiple Linear Regression |
| **Main Tools** | Python (Pandas, Scikit-learn, Statsmodels) |
| **Key Equation** | price = 0.35(area) + 0.20(bathrooms) + 0.19(stories) + ... |

## 🚀 Analysis Workflow
1. **Data Preprocessing:** Handled categorical variables by converting them into binary (1/0) values for features like `mainroad`, `guestroom`, `basement`, and `airconditioning`.
2. **Rescaling:** Applied Min-Max scaling to numerical features to ensure all variables contribute equally to the model.
3. **Model Building:** * Split data into training and testing sets.
    * Used **Recursive Feature Elimination (RFE)** to select the top 10 most impactful features.
    * Refined the model using **VIF (Variance Inflation Factor)** to remove multicollinearity.
4. **Residual Analysis:** Validated the model by checking the error terms' distribution to ensure they were normally distributed.
5. **Evaluation:** Visualized the relationship between predicted prices (`y_pred`) and actual prices (`y_test`) to confirm model accuracy.

## 🛠️ Tech Stack
* **Data Manipulation:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Machine Learning:** `sklearn` (LinearRegression, RFE), `statsmodels`

## 📂 Project Structure
* `Project 01.ipynb` - The full pipeline from data cleaning to model evaluation.
* `Housing.csv` - The dataset used for training the regression model.

---
*Developed as part of an Internship project.*
