# Quote-Analysis
# 📊 Quote Analysis Dashboard (Power BI)

This project presents an end-to-end data pipeline where quotes were scraped from the web, cleaned and transformed using Python and Power BI, and then visualized in an interactive dashboard.


---

## 🔗 Live Demo / Preview

🖼️ See screenshots 
📁 Power BI file: [`Quote_Analysis_Dashboard.pbix`](./Quote_Analysis_Dashboard.pbix)

---

## 🚀 Project Overview

- **Source:** [quotes.toscrape.com](http://quotes.toscrape.com/)
- **ETL Pipeline:**
  - **Extract:** Web scraping using `requests` and `BeautifulSoup`
  - **Transform:** Cleaned nulls, removed special characters, calculated quote length
  - **Load:** Loaded data into Power BI via CSV for analysis

---

## 📊 Dashboard Features

### ✅ Overview Page
- KPI Cards: Total Quotes, Unique Authors, Total Tags, Average Quote Length
- Donut Chart: Deep vs Simple Quote Distribution
- Slicers: Filter by Author, Tag, Quote Type

### ✅ Quote Type Analysis
- Avg quote length by type (Deep vs Simple)
- Top 10 Deep Quotes (by length)
- Histogram of quote length distribution
- Donut chart filtered by selected tag

### ✅ Tag Insights
- Most and Least Used Tags (Used Tooltip)
- Bar chart showing tag frequency

---

## 🧰 Tech Stack

| Tool            | Purpose                            |
|-----------------|------------------------------------|
| `Python`        | Web scraping and transformation    |
| `Pandas`        | Data wrangling                     |
| `Power BI`      | Visualization and interactivity    |
| `DAX`           | Calculated columns & logic         |
| `Power Query`   | Data cleaning & shaping            |

---


---

## 💡 Insights from Data

> “Deep quotes tend to be longer and often associated with philosophical or emotional tags like ‘truth’, ‘life’, and ‘love’. Simple quotes are shorter and often humorous or light-hearted.”

---

## 📌 How to Use

1. Clone/download this repo
2. Open the `.pbix` file in Power BI Desktop
3. Explore and interact with filters, slicers, and visuals

---

## 📈 Future Improvements

- Automate ETL using **Apache Airflow**
- Store data in **SQL database** or **cloud storage**
- Add **real-time updates** using APIs or scheduled scraping
- Host dashboard in Power BI Service

---

## 🙋‍♀️ About Me

**Khushboo Chaudhari**  
🎓 Data Science & Big Data Analytics Graduate  
📧 khushboochaudhari224@gmail.com  

---

⭐ *If you found this useful, consider starring the repo!*

