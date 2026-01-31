# 🍔 Food Delivery Data Analysis

This project focuses on integrating and analyzing food delivery data from multiple real-world data sources.
The goal is to combine transactional, user, and restaurant datasets and extract meaningful business insights using Python.

---

## 📌 Project Overview

In real-world systems, data is often stored in different formats and sources.
This project demonstrates how to:

- Load data from CSV, JSON, and SQL
- Merge datasets using proper relational keys
- Create a final unified dataset
- Perform business-focused data analysis

---

## 📂 Datasets Used

### 📄 File 1: orders.csv (Transactional Data)
Contains order-level information such as order amount, date, user, and restaurant references.

Link:
https://drive.google.com/file/d/1KSA1SskPGwUsn9u3l5LPEgD_vwkXIAf2/view

---

### 📄 File 2: users.json (User Master Data)
Contains user details including city and membership type (Gold / Regular).

Link:
https://drive.google.com/file/d/1O4gvGQvORNkRh8wMjsKyK03At96rFa8p/view

---

### 📄 File 3: restaurants.sql (Restaurant Master Data)
Contains restaurant-level information such as restaurant name, cuisine, and ratings.

Link:
https://drive.google.com/file/d/1uCRWf-xW5OKk6CrHIUJWRcGrG-PR5QVo/view

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- SQLite
- Jupyter Notebook

---

## 🔗 Data Integration Strategy

The datasets were merged using LEFT JOINs to preserve all order records:

- orders.user_id → users.user_id
- orders.restaurant_id → restaurants.restaurant_id

---

## 📊 Key Analyses Performed

- Order trends over time
- User behavior patterns
- City-wise performance
- Cuisine-wise revenue analysis
- Membership impact (Gold vs Regular)
- Revenue distribution and seasonality

---

## 📁 Output

- Final merged dataset:
  final_food_delivery_dataset.csv

---

## 🚀 Future Improvements

- Add visualizations using Matplotlib / Seaborn
- Build an API layer using FastAPI
- Generate insights using Generative AI
- Create interactive dashboards

---

## ✅ Conclusion

This project demonstrates end-to-end data handling, closely reflecting real-world data engineering and analytics workflows.

---

## 👤 Author
Your Name
