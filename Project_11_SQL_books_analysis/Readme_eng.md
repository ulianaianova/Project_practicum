# SQL Project: Subscription-Based Book Service Analysis

SQL-based analytics for a major digital book platform.

---

## Research Objectives

- Determine the number of books published **after January 1, 2000**
- For each book, calculate the **number of reviews and average rating**
- Identify the **publisher with the most books** over 50 pages
- Find the **author with the highest average rating**, among those with over 50 ratings
- Calculate the **average number of reviews** made by users who left **more than 48 ratings**

---

## Tools & Technologies

- **SQL (PostgreSQL)**
- **Jupyter Notebook**
- **Pandas**, **SQLAlchemy** (for querying and data visualization)

---

##  SQL Techniques & Functions Used

- Aggregation: `COUNT`, `AVG`, `ROUND`
- Filtering: `WHERE`, `HAVING`, `IN`
- Working with dates: `EXTRACT`, `::date`, filtering by `publication_date`
- Table joins: `JOIN`, `LEFT JOIN`, `WITH` (CTE)
- Conditional logic: `CASE`, `GROUP BY`, `ORDER BY`
- Subqueries and nested logic

---

## Key Insights

- **819 books** were published after January 1, 2000
- Every book received ratings and reviews; average values were calculated
- **Penguin Books** is the top publisher with **42 books** over 50 pages
- **J.K. Rowling / Mary GrandPré** is the highest-rated author (**4.28**) among those with 50+ ratings
- Users who gave more than 48 ratings left an average of **24 reviews**
