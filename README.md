# 🍽 Restaurant Tipping Behaviour Analysis

## 💡 Project Overview
This project investigates the factors influencing how restaurant customers tip, focusing on *gender, **meal time, **day of the week, and **group size*.  
The goal was to uncover *patterns in tipping behavior* and understand what drives customers to give higher or lower tips.

The analysis was performed using *Microsoft Excel* for data cleaning and statistical exploration, and *Power BI* for visualization and dashboard reporting.  
Both *correlation* and *regression analyses* were applied to identify key relationships between variables.

---

## 🎯 Objectives
The analysis was guided by the following research questions:

1. Does gender influence the percentage of tips given?  
2. How does meal time (Lunch vs. Dinner) affect tipping behavior?  
3. Which days of the week yield the highest average tip percentages?  
4. How does group size relate to the total bill and tipping rate?  
5. What is the relationship between total bill amount and tip percentage?

---

## 🧹 Data Cleaning
The dataset underwent thorough cleaning and preprocessing to ensure accuracy and reliability:

- Removed one duplicate record, leaving *243 valid transactions*
- Renamed and standardized column headers for clarity (e.g., sex → Gender, total_bill → Total Bill)
- Computed *Tip Percentage = (Tip ÷ Total Bill) × 100*
- Encoded categorical variables (Gender, Smoker, Day, Time) for analysis
- Verified data consistency and corrected anomalies or outliers

---

## 🧮 Tools & Techniques Used
- *Microsoft Excel* → Data cleaning, descriptive statistics, correlation & regression  
- *Power BI* → Data visualization and interactive dashboard creation  
- *Statistical Analysis:*
  - CORREL() → Correlation coefficient calculation  
  - *Regression Analysis* → Relationship between predictors and tip percentage  
  - *Descriptive Statistics & Pivot Tables* → Summaries, averages, and trends  

---

## 📈 Key Analyses & Results

### 1️⃣ Gender Differences in Tipping
*Insight:* Gender differences are minimal.  
- Female customers tip an average of *16.7%*
- Male customers tip *15.8%*
- The *0.9 percentage-point difference* is not statistically significant.

*Visual:* Clustered Column Chart  

---

### 2️⃣ Effect of Meal Time (Lunch vs. Dinner)
*Insight:* Lunch time generally yields higher tips.  
- Lunch: *16.4% average tip*
- Dinner: *16.0% average tip*
- Difference suggests meal time has minimal impact.

*Visual:* Line Chart Comparing Meal Times  

---

### 3️⃣ Day-of-Week Patterns
*Insight:*  
- *Friday (17.0%)* and *Sunday (16.7%)* show the highest tip percentages.  
- *Saturday (15.3%)* shows the lowest.  
Customer mood and occasion likely influence generosity.

*Visual:* Column Chart by Day  

---

### 4️⃣ Group Size and Tipping Relationship
*Insight:*  
- Larger groups pay higher *total bills* but *not higher tip percentages*.  
- Strong positive correlation between *group size and total bill (r = 0.598)*.  
- Weak relationship with *tip percentage*, suggesting cost-consciousness.

*Visual:* Scatter Plot with Regression Line  

---

### 5️⃣ Bill Amount and Tip Percentage
*Insight:*  
- Strong positive correlation between *total bill and tip amount (r = 0.675)*.  
- Moderate negative correlation between *total bill and tip percentage (r = –0.339)*.  
Customers tend to *tip lower percentages on higher bills*.

*Visual:* Dual-Axis Chart (Total Bill vs. Tip Amount & Tip %)

---

## 🧠 Methodology
This analysis was conducted on *243 restaurant transactions* after cleaning.

*Techniques Used:*
- Descriptive Statistics → Mean, Median, Mode, Range  
- Correlation Analysis → Relationship strength  
- Regression Analysis → Predictive modeling  
- Full decimal precision maintained for Power BI integration  

---

## 🧭 Business Implications
- Service quality and customer experience outweigh demographic factors.  
- *Weekend service* should be leveraged for higher tipping potential.  
- *Large group management* strategies should ensure fair tipping.  
- Staff training should focus on *consistency and personalized experience*.  
- Billing strategies should balance *total revenue vs. tip fairness*.

---

## 📊 Power BI Dashboard Summary
The interactive dashboard — *Tipping Behaviour Insights* — highlights:

- Average Tip Percentage  
- Average Total Bill  
- Tipping Breakdown by Gender, Day, and Meal Time  
- Correlation visuals (Bill, Tip, Group Size)  
- Regression Summary & Predictive Trends  

🖥 The dashboard enables *data-driven decisions* for restaurant managers and analysts.

---

## ✨ Author
*Toheeb Bello*  
Data Analyst | Business Intelligence Enthusiast | Passionate about Consumer Behaviour Analytics  

---

## 📬 Contact
📧 *Email:* softkidonline@gmail.com  
🌐 *GitHub:* [TOHEEB-BELLO](https://github.com/TOHEEB-BELLO)  


---

> “Data is not just numbers — it’s a story waiting to be told.”  
> — Toheeb Bello
