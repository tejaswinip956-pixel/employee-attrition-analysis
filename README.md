# Employee Attrition Analysis

An end-to-end data analytics project that finds **why employees leave** and **who is most at risk**, using Python for analysis and Power BI for an interactive dashboard.

![Dashboard](Employee_Attrition_Dashboard%20%282%29.png)

## Business problem
HR wants to understand the drivers of employee attrition so it can take action before good employees leave.

## Dataset
IBM HR Analytics Employee Attrition & Performance (Kaggle): 1,470 employees, 35 columns.
Note: this is a fictional dataset created by IBM data scientists, so findings are for learning and demonstration.

## Tools
- Python (Pandas, Seaborn, Matplotlib) in Jupyter Notebook
- Power BI (DAX measures, slicers, interactive dashboard)

## Approach
1. Loaded and inspected the data (shape, types, missing values, attrition split)
2. Cleaned the data (dropped constant and ID columns)
3. Exploratory data analysis (attrition by overtime, role, income, tenure, age, travel)
4. Created groups for income and tenure
5. Built a Power BI dashboard with KPI cards, slicers and charts
6. Wrote findings and recommendations

## Key findings
- Overall attrition rate is **16.1%** (237 of 1,470 employees).
- Employees working **overtime** left at **30.5%** vs **10.4%** for others (about 3x higher).
- **Sales Representatives** have the highest attrition at **39.8%**.
- The **low income** group leaves at **29.3%**, compared to about 10% for high income groups.
- Employees with **0-2 years** of tenure leave at **29.8%**; attrition falls to 8.1% after 10 years.
- **Frequent travellers** leave at **24.9%** vs 8.0% for non-travellers.
- **Single** employees working overtime have the highest attrition at **49.6%**.

## Recommendations
1. Review overtime policies, especially for high-attrition roles.
2. Focus retention efforts on Sales Representatives.
3. Benchmark and review pay for the low income group.
4. Strengthen onboarding and mentoring in the first 2 years.
5. Reduce unnecessary travel or offer travel allowances.
6. Track attrition by role, income and tenure regularly.

## Files
| File | Description |
|---|---|
| `Employee_Attrition_Analysis.ipynb` | Python analysis notebook |
| `WA_Fn-UseC_-HR-Employee-Attrition.csv` | Original dataset |
| `Employee_Attrition_Dashboard.pbix` | Power BI dashboard |
| `dashboard.png` | Dashboard screenshot |

## Author
Tejaswini Patil
