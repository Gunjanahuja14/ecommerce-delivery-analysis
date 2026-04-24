# E-commerce Delivery Performance Analysis

## Overview
This project analyzes delivery performance using the Olist Brazilian E-commerce dataset. The goal is to understand delivery delays, identify factors affecting them, and evaluate their impact on customers.

---

## Objective
- Analyze delivery time and delays  
- Identify factors influencing delays  
- Understand customer impact of delayed deliveries  

---

## Dataset
This project uses the **Olist Brazilian E-commerce Dataset** available on Kaggle:

🔗 https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce  

The dataset contains multiple tables. The following datasets were used:
- Orders  
- Customers  
- Order Items  
- Payments  

Note: Due to large file sizes, the dataset is not included in this repository.

---

## Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Google Colab  

---

## Project Workflow

### 1. Data Loading
Multiple datasets were loaded and prepared for analysis.

### 2. Data Merging
Datasets were merged using keys such as `customer_id` and `order_id` to create a unified dataset.

### 3. Data Cleaning
- Filtered only delivered orders  
- Handled missing values  
- Converted date columns to datetime format  

### 4. Feature Engineering
New features were created:
- `delivery_time` → time taken for delivery  
- `delay` → difference between actual and estimated delivery  
- `is_delayed` → whether order was delayed  

### 5. Data Analysis
- Univariate Analysis  
- Bivariate Analysis  
- Correlation Analysis  

### 6. Data Visualization
Visualizations were created to identify patterns and trends in delivery performance.

---

## Key Insights
- Around **93% of orders are delivered on time or early**  
- Only **~6–7% of orders are delayed**  
- Most deliveries are completed within **5–20 days**  
- Delivery time shows **seasonal variation across months**  
- Payment type and payment value have **minimal impact on delays**  
- Some extreme delay cases exist (outliers)  

---

## Conclusion
The delivery system is generally efficient, with most orders delivered on time or earlier than expected. Delays occur in a small percentage of cases and are likely influenced by operational or seasonal factors rather than payment-related variables.

---

## Project Files
- `notebook.ipynb` → Complete analysis  
- `report.pdf` → Detailed report  

---

## Author
Gunjan Ahuja
