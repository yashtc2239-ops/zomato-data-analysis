# Zomato Restaurant Data Analysis
**End-to-End Data Analytics Project | VIT Pune 3rd Year Portfolio**

**Author:** Yash Chavan | B.Tech CSE-DS | VIT Pune | 2024-28  
**Tech:** Python · SQL · Power BI · Machine Learning  
**Dataset:** 41,410 Bengaluru restaurants (Kaggle)  
**GitHub:** github.com/yashtc2239-ops/zomato-data-analysis

---

## What This Project Is About

I analyzed 41,410+ Zomato restaurants in Bengaluru to answer
one real business question — **where should Zomato expand next,
and what actually drives restaurant ratings?**

This is not a tutorial project. Every phase was built around
a specific business decision, not just "let's make charts."

---

## Key Results

- Built a custom **Expansion Score algorithm** — Lavelle Road
  scored 95.6/100, identified as the #1 expansion zone
- Random Forest model predicts restaurant ratings with
  **R² = 0.82** (outperforms Linear Regression by 179%)
- Discovered that **customer votes drive 69% of rating
  prediction** — more important than price or cuisine type
- Table booking restaurants rate **0.52 points higher** and
  charge **2.6x more** on average — a clear premium segment
- Only **1.4% of 41,410 restaurants** achieve Excellent rating

---

## Project Phases

| Phase | What I Did |
|-------|------------|
| 1 | Defined business problem using MECE framework |
| 2 | Audited 2 Kaggle datasets — 51,717 rows, 17 columns |
| 3 | ETL pipeline — cleaned to 41,410 rows, fixed dtypes |
| 4 | EDA across 6 business questions |
| 5 | 5 business-driven visualizations (Matplotlib + Seaborn) |
| 6 | 8 SQL queries on SQLite — expansion recommendation |
| 7 | 3-page Power BI dashboard with DAX measures |
| 8 | ML model + custom Expansion Score algorithm |

---

## Tools Used

- **Python** — Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **SQL** — SQLite (8 business queries)
- **Power BI** — 3-page dashboard, 5 DAX measures
- **Jupyter Notebook** — all analysis work
- **Git/GitHub** — version control

---

## ML Model

| Model | R² Score | RMSE |
|-------|----------|------|
| Linear Regression | 0.29 | 0.37 |
| Random Forest | **0.82** | **0.19** |

Top 5 features driving restaurant ratings:
1. Votes (customer engagement) — 69.3%
2. Cost for two — 14.7%
3. Restaurant type — 10.9%
4. Online ordering — 3.0%
5. Table booking — 2.1%

---

## Business Recommendations

1. **Expand** in Lavelle Road, Church Street, St. Marks Road
   (Expansion Score > 80/100)
2. **Prioritize engagement** over price in ranking algorithm
   — votes matter 4.7x more than cost
3. **Partner with premium cuisines** — Modern Indian,
   European, Mediterranean show 4.2+ avg rating but low
   restaurant count
4. **Scale table booking program** — these restaurants charge
   2.6x more and rate significantly higher
5. **Quality programs** needed in Bommanahalli (3.19 avg),
   RT Nagar (3.46 avg) — bottom 10 locations

---

## Files in This Repository

## Files in This Repository

| File/Folder | Description |
|-------------|-------------|
| notebooks/00_dataset_audit.ipynb | Raw data audit & schema analysis |
| notebooks/01_cleaning.ipynb | ETL pipeline & data cleaning |
| notebooks/02_eda.ipynb | Exploratory data analysis |
| notebooks/03_visualization.ipynb | Business-driven charts |
| notebooks/04_sql_analysis.ipynb | 8 SQL business queries |
| notebooks/05_advanced_analysis.ipynb | ML model + Expansion Score |
| sql/business_queries.sql | SQL queries reference file |
| reports/expansion_score.png | Expansion priority chart |
| reports/feature_importance.png | ML feature importance chart |
| reports/Phase8_Business_Report.txt | Full business analysis report |
| dashboard_page*.png | Power BI dashboard screenshots |
