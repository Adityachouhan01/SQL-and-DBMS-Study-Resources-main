<div align="center">

<img src="https://raw.githubusercontent.com/onimur/.github/master/.resources/git-header.svg" width="100%" alt="header"/>

<br/>

<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL"/>
<img src="https://img.shields.io/badge/SQL-Database-orange?style=for-the-badge&logo=databricks&logoColor=white" alt="SQL"/>
<img src="https://img.shields.io/badge/Level-Beginner%20to%20Advanced-blue?style=for-the-badge" alt="Level"/>
<img src="https://img.shields.io/badge/Resources-6%20Categories-green?style=for-the-badge" alt="Resources"/>
<img src="https://img.shields.io/github/stars/AdityaChouhan01/mysql-complete-guide?style=for-the-badge&color=yellow" alt="Stars"/>
<img src="https://img.shields.io/github/forks/AdityaChouhan01/mysql-complete-guide?style=for-the-badge&color=orange" alt="Forks"/>

<br/><br/>

# 🗄️ Complete MySQL & SQL Learning Hub

### The most organized MySQL resource collection — from basic queries to advanced concepts.
### Notes · Interview Qs · Query Problems · Handwritten Notes · Practice Sheets · Cheatsheets

<br/>

> ⭐ **Star this repo** if it helped you — it helps more students find it!

<br/>

</div>

---

## 📦 What's Inside

A **complete MySQL study kit** — whether you're learning SQL from scratch, cracking data analyst interviews, or practicing complex queries, everything is organized and ready to use.

| Folder | Contents | Best For |
|--------|----------|----------|
| 📝 `notes/` | Clean, structured MySQL theory notes | Beginners & revision |
| ❓ `interview-questions/` | Top SQL/MySQL interview Q&A | Job & placement prep |
| 💻 `coding-questions/` | SQL query problems with solutions & explanations | Query practice |
| ✍️ `handwritten-notes/` | Scanned handwritten notes for quick revision | Visual learners |
| 📋 `practice-sheets/` | Topic-wise query practice sheets | Daily practice |
| 📄 `cheatsheets/` | Quick reference for SQL syntax & functions | Fast revision |

---

## 📚 Topics Covered

<details>
<summary><b>🔰 SQL & MySQL Basics</b></summary>

- What is a Database? RDBMS concepts
- MySQL installation & setup
- Creating & managing Databases and Tables
- Data Types in MySQL (INT, VARCHAR, DATE, FLOAT, etc.)
- INSERT, SELECT, UPDATE, DELETE (CRUD operations)
- WHERE clause & filtering data

</details>

<details>
<summary><b>🧱 Intermediate SQL</b></summary>

- JOINs: INNER, LEFT, RIGHT, FULL OUTER, CROSS, SELF
- GROUP BY, HAVING, ORDER BY
- Aggregate Functions: COUNT, SUM, AVG, MIN, MAX
- Subqueries & Nested Queries
- DISTINCT, LIMIT, OFFSET
- NULL handling: IS NULL, COALESCE, IFNULL

</details>

<details>
<summary><b>⚙️ Advanced MySQL</b></summary>

- Stored Procedures & Functions
- Triggers & Events
- Views & Materialized Views
- Indexes & Query Optimization
- Transactions: COMMIT, ROLLBACK, SAVEPOINT
- ACID Properties
- Window Functions: ROW_NUMBER, RANK, DENSE_RANK, LEAD, LAG

</details>

<details>
<summary><b>🗂️ Database Design</b></summary>

- Entity-Relationship (ER) Diagrams
- Normalization: 1NF, 2NF, 3NF, BCNF
- Primary Key, Foreign Key, Constraints
- One-to-One, One-to-Many, Many-to-Many relationships
- Schema Design best practices

</details>

<details>
<summary><b>🎯 Interview Preparation</b></summary>

- Top 100 SQL interview questions with answers
- Difference-based questions (DELETE vs TRUNCATE vs DROP, etc.)
- JOIN-based tricky queries
- Window function interview Qs
- Normalization scenario questions
- Real-world query problems asked at MNCs

</details>

---

## 🚀 How to Use This Repo

```bash
# Clone the repo
git clone https://github.com/AdityaChouhan01/mysql-complete-guide.git

# Go inside
cd mysql-complete-guide

# Open in VS Code
code .
```

Or just **browse folders directly on GitHub** — no setup needed!

---

## 💡 Practice Queries — Quick Sample

```sql
-- Find the second highest salary
SELECT MAX(salary) AS second_highest
FROM employees
WHERE salary < (SELECT MAX(salary) FROM employees);

-- Count employees per department
SELECT department, COUNT(*) AS total
FROM employees
GROUP BY department
ORDER BY total DESC;

-- Find duplicate emails
SELECT email, COUNT(*) as count
FROM users
GROUP BY email
HAVING count > 1;
```

> More solved problems inside the `coding-questions/` folder!

---

## 🗺️ Who Is This For?

- 🎓 **Students** learning SQL/databases for the first time
- 💼 **Job seekers** preparing for data analyst / backend / full-stack interviews
- 🧑‍💻 **Developers** who need a quick SQL reference
- 📊 **Aspiring data analysts** building their SQL skills
- 📚 **Self-learners** who want structured notes alongside online courses

---

## ⭐ Why This Repo?

- ✅ **Handwritten + typed notes** — best of both worlds
- ✅ **Topic-wise organized** — no hunting around
- ✅ **Real interview Q&A** — questions asked at top product companies
- ✅ **Query problems with solutions** — learn by doing
- ✅ **Covers DB design** — normalization, ER diagrams, keys
- ✅ **Free forever** — open-source, no paywalls

---

## 📂 Folder Structure

```
mysql-complete-guide/
│
├── 📝 notes/
│   ├── 01-sql-basics.md
│   ├── 02-joins.md
│   ├── 03-aggregate-functions.md
│   ├── 04-subqueries.md
│   └── 05-advanced-mysql.md
│
├── ❓ interview-questions/
│   ├── basic-sql-interview-qs.md
│   ├── joins-interview-qs.md
│   ├── advanced-sql-interview-qs.md
│   └── difference-based-qs.md
│
├── 💻 coding-questions/
│   ├── basic-queries/
│   ├── joins-problems/
│   ├── aggregation-problems/
│   └── window-functions/
│
├── ✍️ handwritten-notes/
│   ├── joins-diagram.pdf
│   └── normalization-notes.pdf
│
├── 📋 practice-sheets/
│   ├── week-01-basics.md
│   ├── week-02-joins.md
│   └── week-03-advanced.md
│
└── 📄 cheatsheets/
    ├── sql-syntax-cheatsheet.md
    ├── joins-cheatsheet.md
    └── mysql-functions-cheatsheet.md
```

> ⚠️ Update the folder structure above to match your actual files before pushing!

---

## 🤝 Contributing

Found an error? Want to add more query problems or notes? Contributions are welcome!

1. Fork this repo
2. Create a branch: `git checkout -b add-sql-notes`
3. Commit: `git commit -m "Add: window functions notes"`
4. Push: `git push origin add-sql-notes`
5. Open a Pull Request

---

## 📫 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-%230077B5.svg?logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/AdityaChouhan01)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?logo=gmail&logoColor=white)](mailto:YOUR_EMAIL@gmail.com)

---

## 📜 License

Licensed under the [MIT License](LICENSE) — free to use, share & modify with credit.

---

<div align="center">

**If this saved your time, drop a ⭐ — it means a lot and helps others find this repo!**

Made with 🗄️ and late nights by [Aditya Chouhan](https://github.com/AdityaChouhan01)

<img src="https://profile-readme-generator.com/assets/snake.svg" alt="snake animation"/>

</div>
