# 🛒 Retail Sales Prediction: Analytics & Insights

## 📝 Project Overview
This project is a comprehensive data science study aimed at understanding and predicting sales for a diverse range of products across multiple retail outlets. By leveraging exploratory data analysis (EDA) and machine learning, we aim to identify which properties of products and stores play crucial roles in driving sales performance.

The ultimate goal of this project is to build a predictive model that helps retailers optimize their inventory, shelf placement, and pricing strategies to maximize overall revenue.

---

## 🔍 Exploratory Data Analysis (EDA)
In this phase, we visualized the data to uncover trends, detect outliers, and understand correlations. Here are the **Top 4 Insights** from the analysis:

### 1️⃣ Pricing vs. Sales (Correlation Heatmap)
<img width="936" alt="Heatmap_project3" src="https://github.com/user-attachments/assets/e8f8709f-b80a-46b5-82bf-34bdb2af6651" />

> **Insight:** There is a moderate positive correlation between `Item_MRP` and `Item_Outlet_Sales`. This indicates that higher-priced products are significant contributors to the total store revenue, making pricing strategy a top priority for sales growth.

---

### 2️⃣ Sales Distribution (Item Outlet Sales Histogram)
<img width="887" alt="outletsales_hist" src="https://github.com/user-attachments/assets/2a83e1f9-a66f-4d35-9c91-90675b0841ff" />

> **Insight:** The distribution of `Item_Outlet_Sales` is significantly **right-skewed**, meaning that while most products have low to moderate sales, there is a "long tail" of high-performing items. Identifying the factors behind these top-selling products is a key opportunity for increasing overall revenue.

---

### 3️⃣ Sales Consistency (Item Outlet Sales Boxplot)
<img width="690" alt="outlet_sales_boxplot" src="https://github.com/user-attachments/assets/e81a6bf2-d713-472c-a44f-4ac5e117058c" />

> **Insight:** The sales data contains several high-value outliers. While most products follow a standard sales range, these **"Top Performers"** indicate that certain products or store locations have unique characteristics that drive exceptional success.

---

### 4️⃣ Market Distribution (Outlet Type Countplot)
<img width="835" alt="outlet_type" src="https://github.com/user-attachments/assets/45ac54ac-98eb-4376-82f4-2158a6922f43" />

> **Insight:** **"Supermarket Type 1"** is the most frequent outlet type in our dataset. This store model appears to be the most successful or widely implemented, suggesting it should be the benchmark for analyzing sales performance across other types.

---

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn
