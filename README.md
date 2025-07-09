# Music-Store-Analysis

This project uses SQL to analyze the Chinook music store database. The goal is to understand global music purchasing patterns, customer value, and genre preferences across countries.

---

## 📌 About the Dataset

The Chinook database mimics a real-world online music store. It includes:
- Customers from multiple countries
- Invoices & invoice items
- Artists, albums, and genres
- Track duration, price, and popularity

---

## Key Insights

- 🇺🇸 The **USA** placed the most orders, followed by Canada and Brazil.
- 🏆 The top customer spent **$49.62** — more than any other shopper in the dataset.
- 🏙️ **Paris** generated the highest total revenue of any city (over **$195**).
- 🎸 **Rock** is the most streamed/bought genre, especially in the US, France, and Canada.
- 🎤 **Iron Maiden** was the top-selling Rock artist by track count.
- 🎶 The longest track in the store is over **9 minutes**.
- 💳 Across most countries, **1 customer dominates spending** (top spender per country).
- 🌍 Different countries prefer different genres — **Pop in Canada**, **Rock in France**, **Latin in Brazil**.

---

## 📂 Files Included

- `Music Store Analysis.sql` – Contains all SQL queries used for the analysis.
- `README.md` – You’re reading it :)
- `Music Store SQL queries.docx` - Contains all the KPI's, queries and their outputs along with them.

---

## 🛠 Tools Used

- SQL (PostgreSQL)
- PGAdmin for writing and running queries
- Chinook sample database (~10K rows)

---

## ▶️ How to Reproduce

1. Download and load the **Chinook database** into your SQL client.
   - You can get it [here](https://github.com/lerocha/chinook-database) in SQLite/MySQL/PostgreSQL format.
2. Open `Music Store Analysis.sql`
3. Run queries in order to explore:
   - Revenue by city & country
   - Top customers & invoices
   - Genre & artist popularity
   - Spending behavior per region

---
