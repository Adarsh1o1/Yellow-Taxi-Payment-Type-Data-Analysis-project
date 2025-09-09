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

## 📦 Dataset
- **[Newyork Taxi Trip Data](https://www.kaggle.com/datasets/microize/newyork-yellow-taxi-trip-data-2020-2019)** 

---

## 🛠️ Tools & Libraries  
- **Python** 
- **Pandas, NumPy** → Data preprocessing & analysis  
- **Matplotlib** → Data visualization  
- **SciPy, Statsmodels** → Hypothesis testing & statistical analysis  
- **Kaggle Notebook** → Development environment  

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
![Payment type vs Fare Amount Distribution AND Payment type vs Trip Distance Distribution](https://github.com/Adarsh1o1/Yellow-Taxi-Payment-Type-Data-Analysis-project/blob/main/Images/download.png?raw=true)

![Payment Type and Passenger Count](https://github.com/Adarsh1o1/Yellow-Taxi-Payment-Type-Data-Analysis-project/blob/main/Images/download%20(2).png?raw=true)

![Preference of Payment Type](https://github.com/Adarsh1o1/Yellow-Taxi-Payment-Type-Data-Analysis-project/blob/main/Images/download%20(1).png?raw=true)

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
- 📧 [mailto:adarshkushawha52@gmail.com]  
- 🌐 [https://x.com/adarsh1o1]  

---


