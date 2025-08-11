# amazon-products-analysis
📊 End-to-end Amazon product dataset analysis with Python, Excel, and Power BI — including data cleaning, EDA, visual storytelling, and key insights.
# Amazon Products Analysis

This project analyzes a dataset of **100,000+ Amazon product listings** to uncover insights into product categories, pricing trends, ratings, and reviews. The analysis is performed using **Python** for preprocessing and **Power BI** for visualization.

---

## 📂 Dataset
- **File Name:** Amazon_Products_100k_.xlsx
- **Source:** Provided for analysis
- **Description:** Contains product details including:
  - `product_name`
  - `category`
  - `price`
  - `rating`
  - `review_count`
  - `product_description`

---

## 🛠 Tools & Libraries Used
- **Python**:
  - `pandas` – Data cleaning & manipulation
  - `numpy` – Numerical operations
  - `matplotlib` & `seaborn` – Data visualization
- **Power BI**:
  - For creating interactive dashboards
- **Jupyter Notebook**:
  - For step-by-step data exploration

---

## 📊 Steps Performed

### **1. Data Preprocessing in Python**
- Loaded the dataset using `pandas`
- Handled missing values in price, rating, and reviews
- Converted data types (e.g., price from string to float)
- Removed duplicate records
- Created additional columns (e.g., price category buckets)

### **2. Exploratory Data Analysis (EDA)**
- Distribution of products by category
- Price range trends
- Rating distribution
- Correlation between price and ratings

### **3. Power BI Dashboard**
- Imported cleaned dataset into Power BI
- Created a **Star Schema** (if applicable)
- Built interactive visuals:
  - Top categories by product count
  - Average rating by category
  - Price distribution charts
  - Review trends
- Applied DAX measures for key metrics

---

## 🔍 Key Insights
- Certain categories dominate the marketplace
- Higher-rated products often cluster in mid-price ranges
- Categories with higher average prices tend to have fewer reviews
- Seasonal or category-specific trends visible in top-selling items

---
