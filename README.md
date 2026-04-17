# IAIP
---

## 📊 Superstore Sales Data Analysis

### 📌 Project Overview

This project focuses on analyzing a retail **Superstore dataset** to uncover insights such as sales trends, product performance, regional distribution, and profitability.
Using Python libraries, the data is cleaned, processed, and visualized to support data-driven decision-making.

---

### 🎯 Objectives

* Analyze **sales trends over time**
* Identify **top-performing products**
* Understand **category-wise and region-wise performance**
* Perform **profit analysis**
* Explore **seasonal patterns**
* Identify relationships between variables using correlation

---

### 🛠️ Tools & Technologies

* Python 🐍
* Pandas (Data Manipulation)
* Matplotlib (Data Visualization)
* Seaborn (Advanced Visualization)

---

### 📂 Dataset

* File: `superstore.csv`
* Records: 51,290 rows
* Features: 27 columns including:

  * Sales, Profit, Quantity
  * Customer & Product details
  * Order & Shipping data

---

### ⚙️ Steps Performed

#### 1. Data Loading

* Imported dataset using Pandas

#### 2. Data Cleaning

* Converted date columns (`Order.Date`, `Ship.Date`) to datetime
* Removed duplicate records
* Checked for missing values (none found ✅)

#### 3. Feature Engineering

* Extracted:

  * Year
  * Month
  * Month Name

#### 4. Data Analysis & Visualization

The following analyses were performed:

1. 📈 **Monthly Sales Trend**
2. 📊 **Yearly Sales Comparison**
3. 🏆 **Top 10 Products by Sales**
4. 📦 **Category-wise Sales**
5. 🌍 **Region-wise Sales**
6. 📅 **Seasonal Sales Distribution**
7. 💰 **Profit by Category**
8. 🔥 **Correlation Heatmap**

---

### 📊 Key Insights (Example)

* Sales vary significantly across months indicating **seasonality**
* Certain products contribute disproportionately to revenue
* Profit is not always aligned with sales (important business insight)
* Discounts impact profitability

---

### 💾 Output

* Cleaned dataset saved as:
  `cleaned_superstore.csv`

---

### ▶️ How to Run the Project

1. Install required libraries:

```bash
pip install pandas matplotlib seaborn
```

2. Run the Python script:

```bash
python your_script_name.py
```

3. Ensure dataset is in the same directory:

```bash
superstore.csv
```

---

### 📸 Sample Visualizations

* Line Chart: Monthly Sales Trend
* Bar Chart: Yearly Sales
* Heatmap: Correlation Analysis
* Boxplot: Seasonal Trends

---

### 🚀 Future Improvements

* Build an interactive dashboard using Power BI / Tableau
* Apply predictive analysis (forecasting sales)
* Perform customer segmentation (K-Means clustering)

---

### 👩‍💻 Author

**Payal Bhattacharya**

---

<img width="1118" height="652" alt="image" src="https://github.com/user-attachments/assets/4fea18f7-ae72-4666-b8fc-e39b34cbcff7" />
