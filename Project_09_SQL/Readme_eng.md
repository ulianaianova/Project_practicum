## SQL Tasks — StackOverflow Database Analysis

Analyze the database of **StackOverflow** — a Q&A platform for programmers that functions like a social network:  
Users ask questions, post answers, leave comments, and rate each other’s content.

---

### Tools & SQL Functions Used

- **PostgreSQL**
- Core SQL statements: `SELECT`, `JOIN`, `GROUP BY`, `HAVING`, `WHERE`, `ORDER BY`, `LIMIT`
- **Aggregations:** `COUNT`, `AVG`, `SUM`, `MIN`, `MAX`, `ROUND`
- **Window Functions:** `ROW_NUMBER`, `DENSE_RANK`, `LAG`, `SUM(...) OVER (...)`
- **Conditional Logic:** `CASE`, `LIKE`, `IN`, `BETWEEN`, `IS NOT NULL`
- **Date Functions:** `EXTRACT`, `DATE_TRUNC`, `::date`, `INTERVAL`
- **Subqueries** and **CTEs (`WITH`)**

---

### Key Objectives

- Identify the most popular questions and top contributors
- Analyze user behavior by country (e.g., Canada)
- Study time-based activity patterns
- Highlight leaders by post count and view count
- Calculate daily user growth
- Explore user engagement trends on a weekly and monthly basis
