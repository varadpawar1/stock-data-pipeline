## 🚀 Stock Market ETL Pipeline | AWS S3 → Snowflake

This project demonstrates a real-world cloud ETL pipeline using AWS S3, Snowflake, and SQL-based transformations to extract insights from historical stock data.

---

### 📌 Project Overview

- **Extract**: Pulled `all_stocks_5yr.csv` from AWS S3 bucket  
- **Transform**: Cleaned and analyzed in Snowflake using SQL and window functions  
- **Load/Leverage**: Created final views and a fully interactive Snowflake dashboard

---

### 🔧 Technologies Used

- **AWS S3** – Cloud object storage for raw stock CSV  
- **Snowflake** – Cloud data warehouse for SQL transformation and dashboarding  
- **SQL** – For data transformation and aggregation  
- **Snowsight** – Used to build visual dashboards inside Snowflake

---

### 🧠 Key Transformations

- Calculated 7-day moving averages using `AVG() OVER()`  
- Identified top 10 most volatile stocks using `(high - low)`  
- Analyzed trends for GOOGL and AAPL using time series breakdowns  
- Summarized volume distribution across stocks

---

### 📊 Dashboard Preview

![Dashboard Sample](screenshots/Average_Volatility.png)

---

### 📁 Folder Breakdown

| Folder         | Description                                      |
|----------------|--------------------------------------------------|
| `/queries`     | SQL scripts used to transform and explore data   |
| `/screenshots` | Snaps from Snowsight dashboard                   |
| `/notebooks`   | PySpark notebook (optional)                      |
| `/data`        | (Optional) Local copy or link to S3 dataset      |

---

### 📚 Learnings

- How to connect Snowflake to S3 via IAM and external stages  
- How to write powerful analytic SQL using window functions  
- How to visualize transformations using Snowsight dashboards  
- How to structure an ETL project for real-world pipelines

---

### 🚀 Future Enhancements

- Automate with Python + Snowflake connector  
- Add PySpark processing layer via Databricks  
- Streamlit dashboard version for interactive web output

---

### 📬 Connect with Me

Varad Pawar  
[LinkedIn](https://www.linkedin.com/in/varadpawar)  
varadpawar.111@gmail.com
