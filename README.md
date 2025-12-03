# Customer Churn, CLV & Retention Strategy Analysis

This project analyzes telecom customer churn using machine learning and statistical modeling. It combines **churn prediction, survival analysis, Customer Lifetime Value (CLV) estimation, and retention strategy simulation** to provide actionable insights for reducing customer churn.

---

##  Dataset

The dataset is available at:  
[**Telco Customer Churn Dataset (Kaggle)**](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)

---

##  Key Highlights

- **Dataset:** 7,043 telecom customer records from [Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn).
- **Churn Prediction:** Built a **Random Forest** model with **79% accuracy (AUC = 0.85)**.
- **Survival Analysis:** Applied **Cox Proportional Hazards Model** to estimate when customers are likely to churn.
- **CLV Calculation:** Estimated customer lifetime value using survival probabilities and monthly charges.
- **Retention Strategy Simulation:** Modeled the impact of switching from *Month-to-Month* contracts to longer-term contracts, demonstrating improved retention.

---

##  Tech Stack

- **Programming Language:** Python  
- **Libraries:** pandas, numpy, scikit-learn, lifelines, matplotlib, seaborn, imbalanced-learn  

---

##  Project Workflow

1. **Data Cleaning & Preprocessing**  
   - Handled missing values and converted categorical variables into numeric using one-hot encoding.
   - Normalized and transformed variables for machine learning readiness.

2. **Exploratory Data Analysis (EDA)**  
   - Visualized churn trends based on contract type, tenure, and payment method.
   - Built a **gauge chart** to represent churn probability.

3. **Churn Prediction Model**  
   - Tuned Random Forest with hyperparameter optimization.
   - Evaluated performance using accuracy, AUC, and feature importance.

4. **Survival Analysis**  
   - Used Cox Proportional Hazards (CoxPH) model to analyze time-to-churn.
   - Plotted survival probabilities over tenure for different customer profiles.

5. **Customer Lifetime Value (CLV)**  
   - Combined survival probability with monthly charges to calculate expected lifetime revenue.

6. **Retention Strategy Simulation**  
   - Tested contract upgrade scenarios (Month-to-Month → One Year).
   - Measured survival probability improvement for proactive retention strategies.

---

##  Results

- **Churn Prediction Accuracy:** **79%**  
- **AUC Score:** **0.85**  
- **Retention Simulation:** Longer-term contracts significantly increase survivalprobability.
