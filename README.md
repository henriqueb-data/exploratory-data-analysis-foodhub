# 📘 FoodHub Order Data – Exploratory Data Analysis  
Analyze FoodHub’s online order dataset to uncover patterns in customer behavior, restaurant performance, delivery dynamics, and revenue opportunities.

---

## 🔍 Overview  
- **Goal:** Perform exploratory data analysis (EDA) to extract insights about order behavior, customer engagement, ratings, cuisine popularity, and delivery performance.  
- **Problem Type:** Exploratory Data Analysis (descriptive analytics)  
- **Dataset:** FoodHub online orders dataset (1,898 orders × 9 features).

---

## 🧭 Context  
FoodHub is a food delivery aggregator offering customers access to multiple restaurants through a single platform. As order volume increases, understanding key patterns in cuisine demand, customer satisfaction, order value, and delivery operations becomes essential for improving service quality, customer retention, and revenue.

This project uses descriptive analytics and visual exploration to identify trends and provide data-driven guidance for operational and marketing decisions.

---

## 📊 Data Summary  
- **Focus:** Understanding order patterns, customer engagement, cuisine popularity, delivery performance, and spending behavior.  
- **Key Features:**  
  - Cuisine type and restaurant  
  - Order cost  
  - Rating (1–5 or “Not given”)  
  - Day of the week  
  - Food preparation and delivery times  
- **Data Notes:**  
  - 1,898 orders across 9 variables  
  - No missing values, but 39% of ratings are “Not given”  
  - Categorical and numeric features suitable for descriptive analysis

---

## 🛠 Methods & Concepts Used  
- **Libraries Used:**  
  - `pandas`, `numpy` for data manipulation  
  - `matplotlib`, `seaborn` for visualization  

- **EDA Techniques:**  
  - Univariate distributions (histograms, boxplots, countplots)  
  - Cuisine and restaurant-level demand analysis  
  - Customer frequency analysis  
  - Delivery performance by weekday vs. weekend  
  - Combined total time (prep + delivery) analysis  
  - Revenue estimation based on commission tiers  

- **Key Concepts:**  
  - Exploratory Data Analysis  
  - Descriptive statistics  
  - Grouped aggregations  
  - Visualization-driven insight extraction  

---

## 💡 Actionable Insights  

- Introduce targeted offers to increase average order value for the most popular cuisines. For example, provide a free item for Japanese, American, Italian, or Chinese orders when customers spend $25 or more.  
- Encourage customers to rate their orders by sending immediate post-purchase prompts, increasing the amount of feedback available for assessing satisfaction.  
- Investigate why most customers place only one order to identify potential pain points and opportunities to improve retention.  
- Analyze why weekday deliveries take longer and take corrective actions—for example, offering higher driver compensation during busy weekday periods.

---

## 👤 Author  
**Henrique Barbosa**  
GitHub: https://github.com/henriqueb-data/

