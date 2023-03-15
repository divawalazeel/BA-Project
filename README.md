# 🚀 Olist Business Analysis

## 📌 Introduction
Olist Store is the largest department store in Brazilian marketplaces, connecting small businesses across Brazil with a hassle-free, single-contract solution. This project analyzes customer behavior, product trends, and order patterns from the Olist Store using business intelligence tools.

## 🎯 Project Scope
This project involves:
1. **📊 Data Ingestion**: Extracting, transforming, and loading data into an AWS RDS PostgreSQL database.
2. **📈 Data Analysis & Visualization**: Utilizing Power BI to generate insights on customer demographics, sales trends, and order distribution.
3. **✅ Report Validation**: Ensuring report accuracy by comparing with direct database queries.
4. **📉 Statistical Analysis**: Applying statistical methods to extract meaningful business insights.
5. **💡 Recommendations**: Identifying areas for business improvement based on analysis.

## 🛠️ Prerequisites
### 📦 Required Libraries
Install the following Python libraries:

```bash
pip install pandas psycopg2 dotenv seaborn matplotlib nltk sklearn sqlalchemy
```

### 🗄️ Database Setup
This project uses **AWS RDS PostgreSQL** for data storage. Ensure you have RDS PostgreSQL credentials.

#### 🔑 SQL Authorization
Create a `.env` file named `rds-keys.env` and insert your database credentials:

```env
DB_HOST=XXXXX
DB_NAME=XXXXX 
DB_USERNAME=XXXXX
DB_PASSWORD=XXXXX
DB_PORT=5432
```

## 🏛️ Database Schema
The extracted data undergoes **cleaning, transformation, and loading** into the **AWS RDS PostgreSQL Database**.

![Database Schema](https://github.com/divawalazeel/BA-Project/blob/main/img/database-schema.png)

## 📊 Power BI Dashboard
The Power BI dashboard provides visual insights into customer demographics, sales trends, order distribution, and product performance.

### 📌 Dashboard Preview

![Dashboard Page 1](https://github.com/divawalazeel/BA-Project/blob/main/img/powerbi-p1.png)

![Dashboard Page 2](https://github.com/divawalazeel/BA-Project/blob/main/img/powerbi-p2.png)

## 📢 Conclusion
This project provides comprehensive insights into Olist Store's customer behavior, product performance, and order trends, facilitating data-driven business decisions. Future improvements may include real-time analytics and advanced predictive modeling.

---

<div align="right">
    <b><a href="#top">⬆️ Back to top</a></b>
</div>
