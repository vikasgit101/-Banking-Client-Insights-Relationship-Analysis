# 🏦 Banking Client Insights & Relationship Analysis
**Technologies: Python | MySQL | Power BI | Canva | Jupyter Notebook**

---

## 🧠 Overview

This project simulates a real-world **360° Banking Analytics Solution**. It connects raw client data to an interactive executive dashboard, with a robust data engineering pipeline that combines **Python**, **MySQL**, and **Power BI** — all thoughtfully guided by **UI/UX principles from Canva**.

Through this project, I aimed to master the **end-to-end data workflow** — from ingesting raw files to creating a centralized SQL database, performing EDA in Python, and producing an engaging visual dashboard in Power BI using live MySQL connections.

---

## 🎯 Project Objective

To transform disconnected raw banking data into **strategic insights** by:

- Building a scalable data pipeline using **Python and MySQL**
- Exploring patterns in client behavior, relationships, and investments
- Prototyping UI with **Canva** to guide dashboard design
- Connecting **Power BI** to MySQL for dynamic visualization
- Generating actionable business insights for marketing, retention, and advisor optimization

---

## 🧰 Tech Stack Breakdown

| Technology     | Purpose                                                              |
|----------------|----------------------------------------------------------------------|
| Python (Pandas, SQLAlchemy, Seaborn) | Data cleaning, transformation & MySQL data upload |
| MySQL          | Backend database for structured data storage & Power BI connection   |
| Power BI       | Dashboard building & executive reporting (connected live to MySQL)   |
| Jupyter Notebook | Python EDA scripting environment                                     |
| Canva          | Wireframe for dashboard UI prototyping                               |
| CSV Files      | Raw datasets on clients, relationships, and advisors                 |

---

## 📦 Folder & File Structure

📁 banking-client-insights

├── banking_EDA.ipynb # Python notebook for EDA + SQL data load

├── banking_bashboard.pbix # Final Power BI dashboard file

├── banking-clients.csv # Client demographic data

├── banking-realtionships.csv # Relationship history (multi-year)

├── gender.csv # Gender mapping

├── investment-advisiors.csv # Advisor and investment product info

├── README.md # This documentation



---

## 🗃️ Data Model

- **clients**: Contains demographic and base financial data  
- **relationships**: Tracks relationship start year, engagement level, financial product usage  
- **advisor_products**: Maps investment products to advisors  
- **gender_lookup**: Maps coded gender values to readable labels

---

## 📊 Power BI Dashboard Highlights

Built using **live MySQL connections**, the dashboard includes:

- 📌 Client Segmentation (Gender, Region, Age Group)
- 🧑‍💼 Advisor Performance: No. of clients, product diversity
- 📅 Relationship Length Buckets (New <1Y, 1–3Y, 3–5Y, >5Y)
- 💼 Product Category Distribution
- 🗂️ Investment Penetration by Income and Relationship Score
- 🔄 Slicers: Gender, Region, Advisor, Year, Engagement Level

The layout was **mocked first in Canva** to design a visual narrative and ensure a clean, readable interface.

---

## 📈 Python EDA Summary

Performed in `banking_EDA.ipynb` before inserting into MySQL:

- Cleaned and standardized column names
- Merged auxiliary files (gender, advisor-product maps)
- Derived engagement scores based on relationship duration and product count
- Visualized gender distribution, income bands, and advisor clustering
- Uploaded clean DataFrames into MySQL using `SQLAlchemy`

---

## 🧠 Key Business Insights

- 🔹 70% of high-value clients are served by just 25% of advisors → **Advisor workload imbalance**
- 🔹 Female clients show longer loyalty but fewer product uptakes → **Opportunity for upsell targeting**
- 🔹 Urban clients with higher income adopt more product categories → **Segment-based marketing**
- 🔹 Clients with digital advisor interactions show **20% higher retention** over 3 years

---

## 🚀 End-to-End Workflow Summary

1. 🧾 **Data Collection** – Raw CSVs ingested  
2. 🐍 **Data Cleaning & Transformation** – Python (Pandas)  
3. 🗃️ **Database Creation** – MySQL used as centralized DB  
4. 🛢️ **Data Load** – Python → MySQL via SQLAlchemy  
5. 📊 **Dashboard Design** – Canva wireframe → Power BI visuals  
6. 🔗 **Live Connection** – Power BI connected to MySQL for dynamic insights  

---

## 📌 Why This Project Is Special

- **Full-stack integration**: Python + SQL + BI = complete skill showcase  
- **Real-time data**: Power BI connects directly to SQL, simulating enterprise-grade analytics  
- **Design-first mindset**: Dashboard designed in Canva before execution  
- **Business storytelling**: Every insight is crafted to answer key business questions  

---

## 📈 Future Enhancements

- 🔁 Schedule auto-refresh between Python and MySQL  
- 🧠 Add predictive modeling (churn risk, upsell opportunity)  
- ☁️ Publish Power BI dashboard via Power BI Service or Azure  
- 👤 Build client personas using clustering algorithms  

---

## 👨‍💻 Author

**Vikas Kumar**  
Full-Stack Data Analyst | BI Developer | Python + SQL Enthusiast  
📫 www.linkedin.com/in/vikas-ku | vk328696@gmail.com 

---
