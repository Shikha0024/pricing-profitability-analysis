# Pricing & Profitability Analysis
**Tools:** SQL (MySQL) · Python (pandas, matplotlib, seaborn) · Tableau Public
**Dataset:** Superstore Sales — 9,994 orders · 3 categories · 4 regions · 2014–2017

---

## Business Problem
A retail company offers discounts across all product categories to drive 
sales volume. This analysis investigates whether discounting is generating 
profitable growth — or destroying margin — and provides data-backed 
strategic recommendations.

---

## Tools & Approach
| Step | Tool | What I did |
|------|------|------------|
| Data storage | MySQL | Loaded 9,994 rows into superstore_db |
| Extraction | SQL — 5 queries | Margins, discount bands, BCG classification |
| Analysis | Python — pandas | EDA, cleaning, 3 charts |
| Visualisation | Tableau Public | 3-chart interactive dashboard |
| Portfolio | GitHub | This repository |

---

## Key Findings
1. **Furniture has only 2.49% margin** despite $741K revenue — heavy discounting is the cause
2. **Discounts above 20% destroy profit** — 1,166 orders with 30%+ discount losing $125,007 total
3. **West region leads** with 14.94% margin and 37.9% of total profit
4. **8 Star products identified** — Labels, Paper, Copiers, Phones (high growth + high margin)
5. **Tables is loss-making** — -8.56% margin losing $17,725 annually at 26% avg discount

---

## Strategic Recommendations
1. **Cap all discounts at 20%** — proven break-even threshold. Estimated recovery: $62,500
2. **Invest in Stars** — Labels, Paper, Copiers, Phones need marketing budget, not discounts
3. **Review Tables and Machines** — Dogs with negative margin, reprice or reduce SKU count
4. **Audit Central region** — lowest margin (7.92%) despite $501K revenue

## Live Dashboard
[View Interactive Tableau Dashboard] https://public.tableau.com/app/profile/shikha.chaudhary3224/viz/Pricing-Profitability-Analysis-Superstore/Dashboard1?publish=yes

## Project Structure
| Folder | Contents |
|--------|----------|
| sql/ | 5 SQL queries — P&L, margins, discount bands, regional ranking, BCG matrix |
| notebooks/ | Python EDA notebook with 3 charts and written findings |
| images/ | Chart screenshots — margin chart, scatter plot, BCG matrix |


## Charts Preview
### Profit Margin by Sub-Category
![Margin Chart](images/01_margin_chart.png)

### Discount vs Profit
![Discount Scatter](images/02_discount_scatter.png)

### BCG Matrix
![BCG Matrix](images/03_bcg_matrix.png)

---

*Prepared by Shikha Chaudhary — MBA (Strategy & Marketing), IIM Udaipur*
