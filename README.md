# Olist E-Commerce — First SQL Analysis

This project is my first end-to-end SQL data analysis. 
I chose to work on a real database to test my skills, and this particular database because the retail/e-commerce sector aligns with my career interests
To complete this, I tried to answer real e-commerce business questions using SQL and Python.

## Preview 
[View the notebook on nbviewer](https://nbviewer.org/github/quentinsladky/olist-ecommerce-first-sql-analysis/blob/main/olist_analysis_.ipynb)

## Business Questions
1. Top 10 catégories ranked by global income
2. Top 10 most performing sellers 
3. Average cart per seller
4. Which states have customers who spend the most ?
   - 4a. Does SP order more in quantity or price ?
   - 4b. What are the top categories at SP ?
5. Which are the top category among the sellers ?  

## Key Findings
- São Paulo gathers most of transactions : *47 449 Orders, 5 202 955,05BRL Revenue*
- There are three major product categories : low value but high volume, high value and low volume, mid value and mid volume : * 1st = health_beauty 1 258 681BRL, 2nd = watches_gifts 1 205 005BRL, 3rd = bed_bath_table 1 036 988BRL*
- Top seller focus on the last one : *1st = bed_bath_table 1572 sells; 2nd = furniture_decor 1292 sells ; 3rd = bed_bath_table 1277 sells*
- Top categories in São Paulo are : mid-range products and products with high purchase frequency : *1st = bed_bath_table, 5 235 Orders, Revenue 478 284,52 BRL, Average Cart 91,36BRL ; 3rd = watches_gifts, 2281 Orders, Revenue 435 009,92 BRL, Average Cart 190,71BRL*
- This database doesn't have enough information about individual prices inside categories which makes it difficult to establish the real value of each category 

## What I Learned
- Writing complex SQL queries with JOINs and CTEs
- First use of SQL CTEs (WITH clause)
- Translating business questions into SQL queries
- Understanding biases in data analysis
- Working with real-world messy datasets
- Structuring an end-to-end data analysis project

## Skills Demonstrated
`SQL` `Python` `Pandas` `SQLite` `Jupyter` `Data Analysis` `Business Thinking`

## Project Structure
- `olist_analysis.ipynb` — Main Jupyter Notebook (SQL queries + analysis)
- `olist.db` — SQLite database (generated from Kaggle CSV files)
- `olist_analysis.py` — Script to load CSV files into SQLite
- `queries.py` — Raw SQL queries used in the analysis

## How to Run
1. Download the Kaggle Olist dataset : https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce
2. Place the CSV files in the project folder
3. Run `python3 olist_analysis.py` to generate `olist.db`
4. Open `olist_analysis.ipynb` in Jupyter Notebook
