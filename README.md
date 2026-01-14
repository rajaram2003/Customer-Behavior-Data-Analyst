# 🛒 Customer Shopping Behavior Analysis

## 📌 Project Overview
This project focuses on analyzing **customer shopping behavior** using transactional data to gain insights into **purchasing patterns, customer segmentation, product preferences, and subscription behavior**.  
The analysis helps businesses make **data-driven decisions** related to marketing strategy, customer retention, and revenue growth.

---

## 📊 Dataset Summary
- **Total Records:** 3,900 purchases  
- **Total Columns:** 18  
- **Key Features:**
  - Customer demographics: Age, Gender, Location, Subscription Status
  - Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
  - Shopping behavior: Discounts, Previous Purchases, Review Rating, Shipping Type
- **Missing Values:** 37 missing values in the `review_rating` column

---

## 🧹 Data Cleaning & Preparation (Python)
Data preparation was performed using **Python (Pandas)**:
- Loaded the dataset and explored structure using `.info()` and `.describe()`
- Handled missing values using **median imputation**
- Standardized column names for consistency
- Performed feature engineering:
  - Created **age groups**
  - Derived purchase frequency metrics
- Removed redundant columns to improve data quality
- Exported the cleaned dataset to **PostgreSQL** for SQL analysis

---

## 🛠️ Tools & Technologies
- **Programming Language:** Python  
- **Data Analysis:** Pandas, SQL  
- **Database:** PostgreSQL  
- **Visualization:** Power BI  

---

## 🔍 SQL Analysis (PostgreSQL)
SQL queries were used to answer key business questions, including:
- Revenue comparison by **gender**
- Identification of **high-spending customers using discounts**
- Top 5 products based on **average review rating**
- Comparison of purchase amounts by **shipping type**
- Revenue and spending behavior of **subscribers vs non-subscribers**
- Customer segmentation into **New, Returning, and Loyal**
- Revenue contribution by **age group**
- Repeat purchase behavior and subscription likelihood

---

## 📈 Power BI Dashboard
An interactive **Power BI dashboard** was created to visualize:
- Total number of customers
- Average purchase amount
- Revenue by product category
- Subscription status distribution
- Revenue and sales trends by age group
- Product performance insights

🔗 **Dashboard Link:**  
https://your-demo-link.com/

---

## 💡 Key Insights
- Loyal customers contribute the highest share of total revenue
- Customers using express shipping tend to spend slightly more
- Some products are highly dependent on discounts to drive sales
- Subscribers show stronger long-term engagement compared to non-subscribers

---

## 📌 Business Recommendations
- Promote exclusive benefits to increase subscription adoption
- Strengthen loyalty programs for repeat buyers
- Optimize discount strategies to balance revenue and profitability
- Focus targeted marketing on high-revenue customer segments


