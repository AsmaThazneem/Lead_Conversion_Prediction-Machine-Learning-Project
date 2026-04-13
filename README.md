#  Lead Conversion Prediction using Machine Learning

##  Problem Statement
A company collects leads from multiple marketing campaigns and sources such as social media, websites, and referrals. Each lead goes through several stages in the sales pipeline and may or may not convert into a customer.  

The objective of this project is to build a machine learning model that predicts whether a lead will convert into a customer based on historical lead data.

---

##  Project Workflow

1. Data Preprocessing  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Feature Encoding  
5. EDA After Feature Engineering  
6. Model Development  
7. Random Forest Modeling  
8. Feature Selection & Model Optimization  
9. Prediction System  

---

## ⚙️ Technologies Used

- **Programming:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn  
- **Tools:** Jupyter Notebook  

---

##  Models Used

- Decision Tree (with GridSearchCV tuning)  
- Random Forest (tuned and optimized)  

---

##  Model Performance

### Final Model: Random Forest (Reduced Features)

- **Train Accuracy:** ~78%  
- **Test Accuracy:** ~75%  
- **Train-Test Gap:** ~3% (Low Overfitting)  

### 🔄 Comparison (All Features Model)

- Train Accuracy: ~84%  
- Test Accuracy: ~76%  
- Gap: ~8% (Higher Overfitting)  

👉 Final model selected based on better generalization and stability.

---

##  Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  

---

##  Key Insights

###  1. Sales Agent Impact
- Features like `assigned_to` have the highest importance  
- Indicates that the **person handling the lead significantly affects conversion**

---

###  2. Campaign Effectiveness
- Campaigns like **Business Accounting, Python, Digital Marketing** show higher impact  
- Suggests that **marketing strategy influences conversion rates**

---

###  3. Time-Based Influence
- Features like `first_call_hour`, `creation_day`, `first_call_day` are important  
- Indicates **timing of contact plays a key role in conversions**

---

##  Final Conclusion

The tuned Random Forest model with reduced features was selected as the final model as it provides:

- Better generalization  
- Lower overfitting  
- Balanced performance across classes  
- More stable and reliable predictions  

---

##  Business Recommendations

- Focus on **high-performing sales agents** and replicate their strategies  
- Invest more in **high-performing campaigns**  
- Optimize **timing of lead follow-ups** to improve conversion rates  


