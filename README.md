# Customer Shopping Behavior Analysis — Data Analyst Portfolio Project

An end-to-end data analytics project analyzing 3,900 retail transactions to understand what
drives repeat purchases, customer loyalty, and spending behavior — built to practice the full
analyst workflow from raw data to a stakeholder-ready dashboard.

I built this to get hands-on practice across the tools a Data Analyst role actually uses day to
day: cleaning and transforming data in Python, writing business-question SQL beyond basic
aggregates (CTEs, window functions), and turning that analysis into a dashboard someone without
a SQL background could actually use.

## Project Overview

The goal was to go from a raw customer dataset to actionable business recommendations, covering:

**Data Preparation & EDA (Python):** Cleaned and transformed the raw dataset — handled missing
values, standardized columns, and engineered features like age groups and a purchase-frequency
signal.

**Data Analysis (SQL):** Loaded the cleaned data into a local **MySQL** database and wrote
queries to answer 10 core business questions on customer segments, loyalty, and purchase drivers
— plus 5 additional queries I added afterward (customer lifetime value ranking, an RFM-style
Frequency x Monetary segmentation, discount-vs-rating correlation, payment method analysis, and
seasonal category trends).

**Visualization & Insights (Power BI):** Built an interactive dashboard highlighting key
patterns and trends — filterable by gender, category, and shipping type.

**Report & Recommendations:** Wrote up findings and business recommendations tied back to
specific numbers from the analysis, along with limitations and what I'd improve with more time
(e.g. a real RFM model if the dataset had transaction timestamps).

## Repository Structure

| File | Description |
|---|---|
| `customer_shopping_behavior.xlsx` | Raw dataset |
| `Customer_Shopping_Behavior_Analysis.ipynb` | Python notebook — import, cleaning, EDA, feature engineering, MySQL load |
| `customer_behavior_sql_queries.sql` | SQL queries answering 15 business questions (10 core + 5 I added) |
| `customer_behavior_dashboard.pbix` | Power BI dashboard |
| `Business Problem Document.pdf` | Problem framing and approach |
| `Customer Shopping Behavior Analysis.pdf` | Full write-up: methodology, findings, recommendations, limitations |
| `Customer-Shopping-Behavior-Analysis.pptx` | Stakeholder presentation deck |

## How to Run This Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/Vivek-kumar-027/customer-trends-data-analysis-SQL-Python-PowerBI.git
   cd customer-trends-data-analysis-SQL-Python-PowerBI
   ```

2. **Open `Customer_Shopping_Behavior_Analysis.ipynb`**

   Covers:
   - Data import
   - Exploratory data analysis
   - Data cleaning & feature engineering
   - Connection to MySQL

3. **Load the cleaned data into MySQL**
   - Create a local MySQL database
   - Run the notebook's load step to push the cleaned DataFrame into MySQL
   - Open `customer_behavior_sql_queries.sql` and run the queries against the loaded table

4. **Connect MySQL to Power BI**
   - Open `customer_behavior_dashboard.pbix`
   - Point it at your local MySQL database to refresh the dashboard

5. **Review the report and deck**
   - `Customer Shopping Behavior Analysis.pdf` for the full write-up, recommendations, and
     limitations/next steps
   - `Customer-Shopping-Behavior-Analysis.pptx` for the stakeholder-facing summary

## License

MIT — feel free to fork, star, or reference for your own learning.

## About Me

I'm Vivek Kumar, currently pursuing an MCA in AI and Data Science. This is part of my personal
portfolio as I work toward a Data Analyst role — I'm hands-on with SQL, Python, Power BI, MySQL,
and Advanced Excel.

- LinkedIn: [Vivek Kumar](https://www.linkedin.com/in/vivek-kumar-263636235/)
- GitHub: [Vivek-kumar-027](https://github.com/Vivek-kumar-027)

## Thanks for checking out the project!

If you're going through something similar or spot something I could improve, feel free to open
an issue or reach out — always looking to learn from feedback.

Connect with me on LinkedIn: [https://www.linkedin.com/in/vivek-kumar-263636235/](https://www.linkedin.com/in/vivek-kumar-263636235/)
