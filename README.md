# 📊 Bank Customer Churn Analysis Dashboard  
A fully interactive **Power BI dashboard** designed to analyze customer exit (churn) behavior across demographics, financial indicators, and product usage patterns.  
Built end-to-end inside **Power BI**, with an Excel dataset as the only data source.  
All cleaning, modeling, segmentation, KPIs, and visual analytics were developed using **Power Query**, **DAX**, and **Power BI visuals**.

---

## 🔍 Overview  
This dashboard provides insights into:

- Customer distribution across age, credit score, salary & balance groups  
- Monthly exit patterns and churn trends  
- High-risk customer segments  
- Product-based churn indicators  
- Behavior differences across demographic categories  
- Churn drivers using decomposition & drilldowns  

The report includes slicers, bookmarks, segmentation visuals, and a clean UX layout.

---

## 📊 Features  

### **📌 Page 1 – Customer Overview**
Contains customer-level KPIs & segmentation visuals:

- **Total Customers**  
- **Active Customers**  
- **Inactive Customers**  
- **Credit Card Holders**  
- **Non–Credit Card Holders**  
- Segmentation visuals across:  
  - Age Group  
  - Credit Score Category  
  - Salary Band  
  - Balance Group  
  - Gender  
  - Geography  
- Product Holding Distribution  

---

### **📌 Page 2 – Exit (Churn) Analysis**
Focused on churn behavior & high-risk segments:

- **Exit Customers**  
- **Exit Rate**  
- **Active : Exit Ratio**  
- **High-Risk Exit Customers** (Poor/Fair credit score)  
- Monthly Exit Trend  
- Gender-wise Exit Count  
- Exit by Product Holding  
- Exit by Age, Credit Category, Salary & Balance Groups  
- **Decomposition Tree** to identify churn drivers  

---

## 📁 Project Structure  




---

## 🧰 Tools & Techniques 

### **🔧 Power BI Desktop**
Main platform used to build the entire dashboard:
- Importing dataset  
- Designing visuals & UI/UX  
- Creating interactive pages  
- Navigation buttons, slicers, bookmarks  
- KPI cards and segmentation visuals  

---

### **🛠 Power Query (Data Cleaning & Transformation)**
Used for all data preparation tasks:
- Fixing incorrect date formats  
- Changing data types  
- Removing nulls & errors  
- Standardizing category columns  
- Preparing clean fields for segmentation  
- Shaping tables for a star-schema model  

No cleaning was done in Excel — everything was handled in Power Query.

---

### **📐 DAX (Data Analysis Expressions)**
Used to create analytical logic and KPIs:
- Exit Count  
- Monthly Exit Count  
- Exit Rate  
- Active : Exit Ratio  
- High-Risk Exit Customer Count  
- Gender-wise Exit Count  
- Segment-based exit calculations  
- Time intelligence (Month hierarchy)  

DAX powers the entire analytical engine of the dashboard.

---

### **🗂 Data Modeling**
A star-schema model was created:
- Fact Table: `Bank_Churn`  
- Dimension Tables: `CustomerInfo`, `Geography`, `DateTable`  
- Relationships built for accurate filtering & drilldowns  
- Custom Date Table used for monthly analysis  

---

### **📊 Excel (Dataset Source Only)**
Excel was used **only to provide the raw dataset**.  
No processing or formulas were done in Excel.

---

## 🚀 How to Use  
1. Open the PBIX file:  
2. Navigate between:  
- **Customer Overview Page**  
- **Exit Analysis Page**  
3. Use slicers to explore customer segments and churn patterns
4. Refer to:https://drive.google.com/file/d/1V5luQsxd8aaZzRFqXXlOIGJoH2e26nSV/view?usp=drive_link    

 
## 🎯 Purpose  
This project demonstrates skills relevant for:

- Business Intelligence  
- Data Analytics  
- Power BI Dashboard Development  
- Customer Churn Analysis  
- Banking Analytics  
- Segmentation & Predictive Reasoning  
- DAX & Data Modeling  

It showcases complete BI workflow capability—from dataset import to final visualization.

---

## 🖼 Dashboard Preview

```md
![Dashboard Preview](readme_assets/preview.gif)

🤝 Feedback & Contact

This is a portfolio project, and I’m always open to feedback & improvement ideas.

💼 LinkedIn: www.linkedin.com/in/karthik4702

📧 Email: karthik4702@gmail.com

Feel free to reach out or open an issue in the repository. 😊

