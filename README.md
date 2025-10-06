
🎧 Music Store Database Analysis (Advanced SQL)
This project uses Advanced SQL (PostgreSQL/MySQL) to query a mock digital music store database, providing key business intelligence across sales, customer behavior, and inventory. It demonstrates proficiency in complex functions like CTEs and Window Functions to solve difficult analytical problems.

💡 Key Business Questions & Insights
Business Focus	Key Question Answered	Technical Method Highlighted
Sales Performance	Identify the top 5 revenue-generating cities and the countries with the most orders.	SUM() & GROUP BY
Customer Value	Find the single customer who spent the most money in each country.	RECURSIVE CTE & MAX()
Customer Behavior	For every country, determine the single most popular genre by purchases.	Window Function (ROW_NUMBER) & PARTITION BY
Target Marketing	Find the best-selling artist by revenue, and then the top customers who buy their music.	Nested CTEs & JOIN

Export to Sheets
🛠️ Technical Skills Demonstrated
Advanced SQL: Proficiency in writing complex, optimized queries.

CTEs (Common Table Expressions): Used for breaking down multi-step calculations.

Window Functions: Utilized ROW_NUMBER() and PARTITION BY for granular, per-group analysis.

Joins & Aggregation: Mastering the use of multiple JOIN clauses across numerous tables.

📁 Repository Files (The Complete Package)
File	Purpose
Music_Store_database.sql	The database schema and all advanced SQL queries (the core analysis).
xlsx	Raw Data: All underlying Excel/CSV sheets needed to populate the database tables, ensuring the project is 100% reproducible.
MUSIC STORE SQL QUERIES.docx	The documentation detailing the business questions and the corresponding SQL code.

