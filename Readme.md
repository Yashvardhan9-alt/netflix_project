# 🎬 Netflix Data Analysis using SQL

## 📌 Project Overview

This project focuses on analyzing Netflix Movies and TV Shows dataset using SQL. The objective is to extract meaningful insights and solve real-world business problems using structured queries.

This project demonstrates strong skills in **data analysis, SQL querying, and problem-solving**, making it suitable for a Data Analyst portfolio.

---

## 🎯 Objectives

* Analyze distribution of Movies vs TV Shows
* Identify most common ratings
* Explore content by year, country, and genre
* Perform advanced SQL analysis using real-world business questions
* Categorize content based on keywords

---

## 📂 Dataset

* Dataset: Netflix Movies & TV Shows
* Source: Kaggle
* Format: CSV

---

## 🗂️ Database Schema

```sql
CREATE TABLE netflix
(
    show_id      VARCHAR(5),
    type         VARCHAR(10),
    title        VARCHAR(250),
    director     VARCHAR(550),
    casts        VARCHAR(1050),
    country      VARCHAR(550),
    date_added   VARCHAR(55),
    release_year INT,
    rating       VARCHAR(15),
    duration     VARCHAR(15),
    listed_in    VARCHAR(250),
    description  VARCHAR(550)
);
```

---

## 🛠️ Tools & Technologies

* SQL (PostgreSQL)
* Data Cleaning
* Data Analysis

---

## 📊 Business Problems Solved

This project solves **15 real-world business problems**, including:

1. Count Movies vs TV Shows 
2. Most common ratings
3. Movies released in a specific year
4. Top 5 countries with most content
5. Longest movie
6. Content added in last 5 years
7. Content by specific director
8. TV shows with more than 5 seasons
9. Content count by genre
10. Year-wise content analysis (India)
11. Documentary movies
12. Content without director
13. Movies of Salman Khan (last 10 years)
14. Top actors in Indian movies
15. Content categorization (Good vs Bad)

---

## 🔍 Key Insights

* Netflix has a mix of Movies and TV Shows with Movies dominating the platform
* Certain countries contribute significantly more content
* Content production has increased over recent years
* Keyword-based filtering helps categorize content quality

---

## 📁 Project Files

* `netflix_titles.csv` → Dataset
* `Schemas.sql` → Table structure 
* `Business Problems Netflix.sql` → Problem statements
* `Solutions of 15 business problems.sql` → SQL solutions 

---

## 💡 Skills Demonstrated

* SQL Queries (Basic to Advanced)
* Data Cleaning & Transformation
* Aggregations & Window Functions
* Problem Solving
* Analytical Thinking

---

## 📌 Conclusion

This project provides valuable insights into Netflix content trends and showcases the practical application of SQL in solving real-world data analysis problems.

---

## 👨‍💻 Author

**Yash Vardhan**

