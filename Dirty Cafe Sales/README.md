# ☕ Café Sales Data Analysis | From Messy Data to Meaningful Insights

## 📌 Project Overview

This project focuses on cleaning and analyzing a real-world café sales dataset containing ~10,000 transaction records. The dataset initially contained missing values, inconsistent entries (e.g., "ERROR", "UNKNOWN"), and logical mismatches.

The goal was to transform raw, messy data into a clean and structured dataset and extract meaningful business insights using Excel and Power BI.

---

## ⚠️ Problem Statement

Real-world datasets are rarely clean. This dataset contained:

- Missing values across multiple columns  
- Invalid entries such as "ERROR" and "UNKNOWN"  
- Logical inconsistencies (Total ≠ Quantity × Price)  
- Mixed data types  

These issues made the dataset unsuitable for direct analysis.

---

## 🧠 Data Cleaning Approach

Instead of blindly removing data, a dependency-based approach was used:

### 🔗 Key Relationships
- **Total Spent = Quantity × Price Per Unit**  
- **Item → Price Per Unit**

---

### 🔧 Steps Performed

- Recovered **Price Per Unit** using item-price mapping  
- Derived **Quantity** using: