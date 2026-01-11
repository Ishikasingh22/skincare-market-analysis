# skincare-market-analysis
Analysis of the skincare market using Sephora product data to uncover brand performance, pricing patterns, and ingredient trends through Python and Power BI.

# 🧴 Skincare Market Analysis: Brand, Product & Ingredient Insights

## 📌 Project Overview
This project analyzes the **skincare segment of Sephora’s product catalog** to uncover insights related to:
- Brand performance
- Product popularity and pricing
- Most Commonly used Ingredients in Skincare

The objective is to demonstrate **end-to-end data analysis skills** using **Python,and Power BI**, with a strong focus on **business-relevant insights** and data integrity.

---

## 🎯 Business Questions
- Which skincare brands dominate the market in terms of popularity?
- What defines a top-performing skincare product?
- How do pricing and ratings relate to product popularity?
- Which ingredients are most commonly used in skincare products?

---

## 🗂️ Datasets Used

### 1️⃣ Sephora Products Dataset (Primary)
This dataset contains detailed product-level information, including:
- Product and brand identifiers
- Pricing (USD)
- Ratings and reviews
- Popularity metric (`loves_count`)
- Ingredient lists
- Product categories (skincare, makeup, hair, etc.)

This dataset serves as the **main source of analysis**, especially for product and ingredient insights.

---

### 2️⃣ Clean Skincare Dataset (Supplementary)
This dataset includes clean skincare product listings and ingredient-related details.


---

## 🧠 Methodology

### 🔹 Data Cleaning & Preparation (Python)
- Loaded raw datasets using `pandas`
- Standardized text fields (lowercasing, trimming whitespace)
- Filtered products to include **Skincare category only**
- Converted price fields to numeric formats

Python was chosen for cleaning and preprocessing due to its flexibility with unstructured and text-heavy data.

---

### 🔹 Feature Engineering & Analysis
- Created **brand-level performance metrics**:
  - Number of products per brand
  - Average price
  - Average rating
  - Total popularity (`loves_count`)
- Identified **top-performing skincare products**
- Parsed ingredient lists using Python string processing
- Used `collections.Counter` to compute ingredient frequency
- Focused ingredient analysis specifically on **top-performing products**

---

### 🔹 Visualization (Power BI)
Processed analytical tables were exported as CSV files and visualized in **Power BI**, enabling:
- Market overview KPIs
- Brand and product performances
- Ingredient frequency dashboards

---

## 📊 Key Insights
- A small number of brands account for a large share of skincare product popularity.
- Higher-priced products do not always correspond to higher ratings.
- Certain ingredients consistently appear in top-performing skincare products.
- Successful products tend to use combinations of commonly trusted ingredients rather than rare or experimental ones.

---

## ⚠️ Data Limitations
- The clean skincare dataset could not be reliably joined with the Sephora dataset due to missing shared identifiers.
- Ingredient analysis is associative and does not imply causation.
- No time-series forecasting was performed due to lack of historical sales data.

These limitations were intentionally respected to ensure analytical integrity.

---

## 🛠️ Tools & Technologies
- **Python**: pandas, numpy, collections
- **SQL**: relational logic and aggregations (conceptual)
- **Power BI**: interactive dashboards and data storytelling
- **GitHub**: version control and project documentation

---

## 🚀 Future Enhancements
- Incorporate transaction-level sales data for forecasting
- Extend ingredient analysis using customer review sentiment
- Compare ingredient strategies across brands
- Publish interactive dashboards via Power BI Service or portfolio site

---

## 👤 Author
**Ishika**  
Master’s Student | Quant Finance / Data Analytics  
Skills: SQL • Python • Power BI • Data Analysis

