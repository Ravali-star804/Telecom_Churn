# 📞 PRCL-0017 – Customer Churn Prediction (No-Churn Telecom)

## 🏢 Business Overview
**No-Churn Telecom** is an established telecom operator in Europe facing a **high customer churn rate** (more than 10%).  
Despite reducing tariffs and offering promotions, the company continues to lose customers to competitors.  
To improve retention, No-Churn aims to leverage **Machine Learning** to identify customers most likely to leave and take preventive actions.

---

## 🎯 Project Objective
- Analyze customer data to identify **key factors influencing churn**.  
- Develop a **predictive ML model** that assigns a **churn risk score** to each customer.  
- Create a new feature, `CHURN_FLAG`, with:
  - `1` → Customer likely to churn  
  - `0` → Customer likely to stay  
- Enable **targeted retention campaigns** to reduce churn and improve loyalty.

---

## 🧾 Dataset Description
- Contains customer demographics, service usage, billing, and plan details.  
- **Target Variable:** `CHURN_FLAG`  
- Data includes both categorical and numerical features representing:
  - Network usage  
  - Complaints & service requests  
  - Plan type and duration  
  - Monthly charges, tenure, and payment history  

---

## ⚙️ Project Workflow
1. **Data Preprocessing:**  
   - Handled missing values, encoded categorical variables, and normalized numeric features.  
2. **Exploratory Data Analysis (EDA):**  
   - Identified patterns and correlations between churn and customer behavior.  
3. **Feature Engineering:**  
   - Created new features such as customer tenure groups and payment consistency.  
4. **Model Development:**  
   - Trained and compared multiple algorithms:  
     - Logistic Regression  
     - Random Forest  
     - XGBoost  
5. **Model Evaluation:**  
   - Metrics used: Accuracy, Precision, Recall, F1-Score, ROC-AUC.  
   - Selected best-performing model based on recall and AUC (to minimize false negatives).  

---

## 🧰 Libraries Used
```python
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost



📊 Results & Insights

Achieved ~85% accuracy and AUC = 0.90 using XGBoost.

Key churn indicators identified:

Short customer tenure

High monthly charges

Frequent service complaints

Low usage of bundled offers

Provided churn risk list for retention team to target with loyalty offers.

🚀 Business Impact

Enabled data-driven customer retention strategy.

Reduced churn through early intervention.

Improved customer lifetime value (CLV) and overall satisfaction.

🧠 Key Learnings

Combining domain knowledge with ML gives strong business insights.

Feature engineering and handling class imbalance are critical for churn prediction.

Interpretable models (like Logistic Regression) can complement high-performing ones (like XGBoost).

💻 Tools & Environment

Python (Google Colab / Jupyter Notebook)

Version Control: Git & GitHub

Visualization: Matplotlib, Seaborn

ML Framework: Scikit-learn, XGBoost


## 👩‍💻 Author
**Ravali Ambadi**  
Aspiring Data Scientist  
[LinkedIn](www.linkedin.com/in/ravali-ambadi-872772187)
