# Consumer Goods Ad-Hoc SQL Insights
## Codebasics Resume Project Challenge

## Problem Statement
AtliQ Hardwares, a leading computer hardware producer, needed data-driven insights to make quick and smart business decisions. This project solves 10 ad-hoc business requests using MySQL.

## Tech Stack
- MySQL (CTEs, Joins, Subqueries, Window Functions, CASE statements)
- PowerPoint (Insights Presentation)

## Business Questions Answered
| # | Question | SQL Concepts Used |
|---|----------|-------------------|
| 1 | Markets where Atliq Exclusive operates in APAC | DISTINCT, WHERE |
| 2 | Unique product % increase 2020 vs 2021 | CTEs, COUNT DISTINCT |
| 3 | Product count per segment | GROUP BY, ORDER BY |
| 4 | Segment with most product growth 2021 vs 2020 | CTEs, JOIN |
| 5 | Highest & lowest manufacturing cost products | Subqueries, MAX, MIN |
| 6 | Top 5 customers by discount % (India, FY2021) | AVG, Subquery, LIMIT |
| 7 | Monthly gross sales for Atliq Exclusive | JOINS, SUM, MONTHNAME |
| 8 | Quarter with max sold quantity in FY2020 | CASE WHEN, FORMAT |
| 9 | Channel contribution to gross sales FY2021 | CTE, Window Function |
| 10 | Top 3 products per division by sold quantity | RANK(), PARTITION BY |

## Key Insights
- 📈 **36.33%** product growth from FY2020 → FY2021
- 🛒 **Retailer channel** drives 73% of FY2021 gross sales
- 📅 **November** is consistently the peak revenue month
- 🌏 Atliq Exclusive operates in **8 APAC markets**
- 🏆 **Accessories** is the fastest growing segment (+34 products)
