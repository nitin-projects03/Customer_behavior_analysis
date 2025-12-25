# Customer Shopping Behavior Analysis

## 📌 Project Overview
This project focuses on analyzing customer shopping behavior using transactional data to uncover insights into spending patterns, product preferences, customer segments, and subscription behavior.  
The goal is to support data-driven business decisions through end-to-end data analysis.

---

## 🎯 Objectives
- Analyze customer purchase behavior and trends  
- Compare subscribers vs non-subscribers  
- Identify high-value customers and products  
- Understand the impact of discounts and shipping types  
- Present insights through an interactive dashboard  

---

## 📊 Dataset Summary
- **Total Records:** 3,900 purchases  
- **Total Columns:** 18  
- **Data Type:** Transactional customer data  

### Key Features
- Customer demographics (Age, Gender, Location, Subscription Status)  
- Purchase details (Category, Item, Amount, Season, Size, Color)  
- Shopping behavior (Discount Applied, Review Rating, Shipping Type, Purchase Frequency)  

⚠️ Missing values were present in the *Review Rating* column and handled during preprocessing.

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NumPy, Matplotlib) – Data cleaning & EDA  
- **PostgreSQL (SQL)** – Business analysis  
- **Power BI** – Data visualization & dashboard  

---

## 🧹 Data Cleaning & Feature Engineering (Python)
- Checked data structure and summary statistics  
- Handled missing values using category-wise median imputation  
- Standardized column names (snake_case)  
- Created new features:
  - `age_group`
  - `purchase_frequency_days`
- Identified and removed redundant columns  
- Loaded cleaned data into PostgreSQL for analysis  

---

## 🗄 SQL Analysis (Business Insights)
Key business questions answered using SQL:

- Revenue comparison by gender  
- Spending behavior of discount users  
- Top 5 products by average review rating  
- Standard vs Express shipping impact on purchase amount  
- Subscriber vs Non-Subscriber spending comparison  
- Discount-dependent products analysis  
- Customer segmentation (New, Returning, Loyal)  
- Top products per category  
- Relationship between repeat purchases and subscriptions  
- Revenue contribution by age group  

---

## 👥 Customer Segmentation
Customers were segmented based on purchase history:
- **New Customers**
- **Returning Customers**
- **Loyal Customers**

This segmentation helps in designing targeted marketing and retention strategies.

---

## 📈 Power BI Dashboard
An interactive Power BI dashboard was created to visualize:
- Revenue trends  
- Customer segments  
- Product performance  
- Age group contribution  
- Subscription and shipping insights  

The dashboard enables dynamic filtering for deeper analysis.

---

## 💡 Key Insights
- Subscribers show higher average spending  
- Express shipping users tend to make higher-value purchases  
- Certain products rely heavily on discounts  
- Loyal customers are more likely to subscribe  

---

## 🚀 Business Recommendations
- Promote exclusive benefits for subscribers  
- Introduce loyalty programs for repeat buyers  
- Optimize discount strategies to protect margins  
- Focus marketing on high-revenue age groups  
- Highlight top-rated and best-selling products  

---

## ✅ Conclusion
This project demonstrates an end-to-end data analytics workflow, starting from data cleaning and feature engineering in Python, performing structured business analysis using SQL, and presenting insights through an interactive Power BI dashboard. The analysis provided actionable insights into customer behavior, product performance, and subscription trends, reflecting practical skills required for a real-world Data Analyst role.

## 📂 Project Structure
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── data_cleaning_eda.ipynb
│
├── sql_queries/
│   └── business_analysis_queries.sql
│
├── powerbi_dashboard/
│   └── customer_shopping_dashboard.pbix
│
├── presentation/
│   └── customer_shopping_analysis.pptx
│
├── report/
│   └── Customer_Shopping_Behavior_Analysis.docx
│
├── README.md
└── requirements.txt

## 📬 Contact & Acknowledgement

**Nitin Tiwari**  
Aspiring Data Analyst  
Skills: SQL | Python | Power BI | Excel  

🙏 **Acknowledgement**  
This project was developed as a learning exercise with guidance from a YouTube tutorial by **Amlan Mohanty**.  
The data cleaning, SQL analysis, and Power BI dashboard were independently implemented and customized, including changes to dashboard theme, layout, and overall structure.


