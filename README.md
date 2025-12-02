📊 Customer Shopping Behavior Analysis
End-to-End Data Analytics Project

⭐ Overview

This project presents a complete **data analytics workflow** built to understand and interpret **customer shopping behavior** based on transactional data from 3,900 purchases.
The goal is to analyze customer demographics, purchase patterns, subscription behavior, and product preferences to support strategic business decisions.

This project demonstrates proficiency in:
✔ Python (Pandas, NumPy, Matplotlib)
✔ Data Cleaning & Feature Engineering
✔ SQL (PostgreSQL) for analytical queries
✔ Power BI for dashboard building
✔ Report creation & presentation (Gamma App)

## 📁 Dataset Summary

Total Rows: 3,900
Columns: 18
Key Attributes:

Customer Demographics: Age, Gender, Location, Subscription Status
Purchase Details: Item Purchased, Category, Season, Price, Size, Color
Behavioral Data: Discount Applied, Previous Purchases, Frequency, Shipping Type
Review Ratings: 37 missing values (handled during cleaning)

🛠 Tools & Technologies

| Tool                                   | Usage                        |
| -------------------------------------- | ---------------------------- |
| **Python (Pandas, NumPy, Matplotlib)** | Data loading, EDA, Cleaning  |
| **PostgreSQL + pgAdmin**               | Analytical SQL queries       |
| **Power BI**                           | Dashboard development        |
| **Gamma**                              | Automated presentation (PPT) |
| **Jupyter Notebook / VS Code**         | Code execution               |
| **Git**                                | Version control              |

---

🔍 Steps Performed

1️⃣ Data Loading & EDA (Python)

* Loaded the dataset using **Pandas**
* Explored structure with `df.info()` and statistical summaries using `df.describe()`
* Checked missing data and patterns
* Visualized key features and distributions

2️⃣ Data Cleaning

* Imputed missing values in *Review Rating* using category-wise median
* Standardized column names into **snake_case**
* Removed redundant variables (`promo_code_used`)
* Validated consistency between discount and promo code columns

3️⃣ Feature Engineering

* Created **age_group** by binning Age
* Derived **purchase_frequency_days**
* Categorized customers into behavioral segments

4️⃣ SQL Analysis (PostgreSQL)

Cleaned data was loaded into PostgreSQL for structured querying.
Key business questions answered using SQL:

* **Revenue by gender**
* **High-spending discount users**
* **Top 5 products by average rating**
* **Standard vs Express shipping comparison**
* **Subscriber vs non-subscriber revenue difference**
* **Discount-dependent products**
* **Customer segmentation (New, Returning, Loyal)**
* **Top 3 items per category**
* **Subscription likelihood of repeat buyers**
* **Revenue contribution by age group**

5️⃣ Power BI Dashboard

An interactive dashboard was created highlighting:

* Customer demographics
* Revenue trends
* Top-selling products
* Category-level insights
* Shipping preferences
* Subscriber vs non-subscriber spend
* Discount impact analysis

6️⃣ Final Report & PPT

* A detailed PDF report summarizes insights and methods
* Gamma-powered presentation highlights trends, KPIs, and recommendations

---

 📈 Dashboard Overview
<img width="1129" height="632" alt="Screenshot 2025-12-02 170705" src="https://github.com/user-attachments/assets/8fbae345-b5cf-45c7-a3c0-4c37da87a2b3" />


The dashboard provides:

* KPI tiles for revenue, purchase count, and average spend
* Segmentation visuals (age group, gender, subscription)
* Top categories & product performance
* Behavioral insights: discount usage, shipping type preferences

---

🚀 Key Insights & Business Recommendations

1. Boost Subscription Conversions**
Subscribers show higher repeat purchases—offer exclusive discounts and early access.

2. Strengthen Loyalty Programs**
Reward repeat and high-frequency buyers to encourage long-term engagement.

3. Optimize Discount Strategy**
Analyze discount-heavy products to protect margins without hurting sales volume.

4. Prioritize High-Rated & Best-Selling Products**
Use these for marketing campaigns to drive conversions.

5. Target High-Value Segments**
Focus marketing on specific profitable age groups and express-shipping customers.

---

▶️ How to Run the Project

1. Clone the Repository**

```bash
git clone https://github.com/your-username/customer-shopping-behavior.git
cd customer-shopping-behavior
```

2. Install Python Dependencies**

```bash
pip install -r requirements.txt
```

3. Run the Jupyter Notebook**

```bash
jupyter notebook
```

4. Set Up PostgreSQL**

* Create a database
* Import the cleaned dataset
* Run SQL scripts located in: `/sql/`

5. Open Power BI Dashboard**

* Load the `.pbix` file
* Refresh data if required

6. View Reports & Presentation**

* Detailed report in `/reports/`
* Gamma presentation in `/presentation/`


