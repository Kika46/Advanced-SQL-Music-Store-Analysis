🎧 Music Store Database Analysis (Advanced SQL)
This project uses Advanced SQL (PostgreSQL/MySQL) to query a mock digital music store database, providing key business intelligence across sales, customer behavior, and inventory. It focuses on using complex functions like CTEs and Window Functions to solve difficult analytical problems.

💡 Key Business Questions & Insights
-Business Focus	Key Question Answered	Technical Method Highlighted
-Sales Performance	Identify the top 5 revenue-generating cities and the countries with the most orders.	SUM() & GROUP BY
-Customer Value	Find the single customer who spent the most money in each country.	RECURSIVE CTE & MAX()
-Customer Behavior	For every country, determine the single most popular genre by purchases.	Window Function (ROW_NUMBER) & PARTITION BY
-Target Marketing	Identify the best-selling artist by revenue, and then find the top customers who buy their music.	Nested CTEs & JOIN
-Inventory	List all tracks that are longer than the average song length of the entire catalog.	Subquery

Export to Sheets
🛠️ Technical Skills Demonstrated
Advanced SQL: Proficiency in writing complex, optimized queries.
-CTEs (Common Table Expressions): Used for breaking down multi-step calculations (e.g., finding the best artist first, then calculating customer spending on them).
-Window Functions: Utilized ROW_NUMBER() and PARTITION BY for granular, per-group analysis (e.g., popular genre per country).
-Joins & Aggregation: Mastering the use of multiple JOIN clauses across numerous tables to synthesize data for KPIs.
