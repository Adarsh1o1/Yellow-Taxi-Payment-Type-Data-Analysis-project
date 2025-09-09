# 🚖 Taxi Fare Payment Analysis  

## 📌 Overview  
This project analyzes the relationship between **payment methods (cash vs. card)** and **fare amounts** in taxi rides.  
The goal is to identify whether payment type influences revenue and provide **data-driven recommendations** for maximizing taxi driver earnings.  

---

## 🎯 Problem Statement  
Revenue of taxi drivers is a critical factor for their long-term success and satisfaction.  
We aim to determine whether **payment methods impact fare pricing** by focusing on the relationship between **payment type** and **fare amount**.  

**Research Question:**  
➡️ Is there a significant difference in fare amounts between customers who pay using **cash** and those who pay using **credit cards**?  

---

## 🧑‍💻 Objectives  
- Perform **exploratory data analysis (EDA)** to understand taxi fare distributions.  
- Test the hypothesis:  
  - **H₀ (Null Hypothesis):** No significant difference in fares between cash and card payments.  
  - **H₁ (Alternative Hypothesis):** Significant difference exists between cash and card fares.  
- Apply **statistical testing (t-test)** to evaluate results.  
- Provide **recommendations** to maximize driver revenue.  

---

## 🛠️ Tools & Libraries  
- **Python** 🐍  
- **Pandas, NumPy** → Data preprocessing & analysis  
- **Matplotlib, Seaborn** → Data visualization  
- **SciPy, Statsmodels** → Hypothesis testing & statistical analysis  
- **Jupyter Notebook / Kaggle** → Development environment  

---

## 📊 Analysis Workflow  
1. **Data Cleaning & Preprocessing**  
   - Removed missing values and outliers  
   - Encoded categorical variables (payment type)  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of fare amounts  
   - Grouped analysis by payment type  

3. **Hypothesis Testing**  
   - Conducted independent **two-sample t-test (Welch’s t-test)**  
   - **p-value = 0.0 (< 0.05)** → Rejected Null Hypothesis  

4. **Results & Insights**  
   - **Card payments yield higher average fares compared to cash**  
   - Payment type significantly influences revenue  

---

## 📈 Visualizations
**  

---

## ✅ Key Findings  
- **p-value = 0.0 (< 0.05)** → Payment type has a statistically significant effect on fares.  
- Card payments generated **higher average fare amounts** than cash payments.  
- Taxi drivers can potentially **increase revenue** by nudging customers toward card payments.  

---

## 💡 Recommendations  
- Encourage **credit card payments** to maximize driver revenue.  
- Implement **discounts/incentives** for card transactions.  
- Improve **digital payment systems** for seamless and secure experiences.  

---

## 🚀 Future Work    
- Perform **regression Analysis** to predict fares.  

---

## ✨ Author  
**Adarsh Kushwaha**  
- 📧 [adarshkushawha52@gmail.com]  
- 🌐 [x.com/adarsh1o1]  

---


