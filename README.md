# Bassel Allaa - Data Analyst Portfolio

[![Excel](https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)](#) [![SQL](https://img.shields.io/badge/-SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)](#) [![Power BI](https://img.shields.io/badge/-Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](#) [![Python](https://img.shields.io/badge/-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)](#)

**Transforming Data into Actionable Insights**

[View Projects](#featured-projects) • [About Me](#about-me) • [Skills](#technical-skills) • [Contact](#lets-connect)

---

## Welcome!

I'm a data analyst passionate about uncovering stories hidden in data and translating complex datasets into clear, impactful insights. This portfolio showcases my journey from Excel foundations to advanced SQL analytics, interactive Power BI visualizations, and — most recently — a full self-scraped Python data pipeline with real regression modeling.

**What I Do:**

- Business Intelligence & Analytics
- Web Scraping & Python Data Pipelines
- E-Commerce & Retail Analysis
- Interactive Dashboard Development
- Data-Driven Decision Support

---

## Featured Projects

### 1️⃣ UAE Used Car Market Analysis

> **Self-scraped, multi-source Python pipeline analyzing 28K+ real UAE car listings**

**Overview:** End-to-end pipeline scraping three UAE car marketplaces (CarSwitch, AutoTraders.ae, OpenSooq), combining 28,109 listings after cross-source deduplication, then cleaning, exploring, and modeling the data with regression to answer real questions about how the market actually prices cars.

**Key Insights:**

- Controlling for exact make/model/mileage/age, listings priced **~AED 29,861 lower** on CarSwitch than AutoTraders.ae — a real platform pricing effect, the opposite of what the raw price comparison suggested
- Swapping a broad brand-tier feature for the specific model **nearly doubled R²** (0.091 → 0.213), showing exact model matters far more than brand segment for price prediction
- Traced a miscalibrated pricing model to two root causes — classic/collector cars breaking a linear age assumption, and a cult JDM nameplate skewing predictions — and fixed both rather than just reporting a bad number

**Technologies:** `Python` `Pandas` `NumPy` `Requests` `BeautifulSoup` `Scikit-learn` `Matplotlib` `Seaborn` `Jupyter`

**What I Learned:** Multi-source web scraping (including debugging a silent Brotli-encoding bug and reverse-engineering a Next.js API response), fuzzy deduplication across sources, regression modeling with honest train/test evaluation, and how to diagnose *why* a model's output looks wrong instead of just reporting the number.

[**→ View Full Project**](https://github.com/Bassel-allaa/UAE_Used_Car_Market_Analysis)

---

### 2️⃣ E-Commerce Data Analytics

> **End-to-end analysis of Olist Brazilian e-commerce platform**

[![E-Commerce Dashboard](https://github.com/Bassel-allaa/Bassels_Data_Analyst_Portfolio/raw/main/images/dashboard_overview.png)](/Bassel-allaa/Bassels_Data_Analyst_Portfolio/blob/main/images/dashboard_overview.png)

**Overview:** Comprehensive analysis covering sales trends, customer retention, delivery performance, and seller metrics to support data-driven business decisions.

**Key Insights:**

- Customer churn rate of **71%+** identified as critical issue
- Delivery performance at **93% on-time rate**
- Recommended loyalty programs and retention strategies

**Technologies:** `SQL` `PostgreSQL` `Power BI` `Data Cleaning`

**What I Learned:** End-to-end data pipeline from raw data processing to business recommendations

[**→ View Full Project**](https://github.com/Bassel-allaa/E-Commerce_Data_Analytics)

---

### 3️⃣ Superstore Sales Analysis

> **Interactive Excel dashboard for retail performance tracking**

[![Superstore Dashboard](https://github.com/Bassel-allaa/Bassels_Data_Analyst_Portfolio/raw/main/images/Superstore_dashboard.png)](/Bassel-allaa/Bassels_Data_Analyst_Portfolio/blob/main/images/Superstore_dashboard.png)

**Overview:** Analyzed 9,994 orders from 2014-2017 with interactive features including segment filters, order lookups, heatmaps, and trend analysis.

**Key Insights:**

- West region leads in sales performance
- Technology category drives highest profit margins
- High-return items identified as profit erosion factor

**Technologies:** `Excel` `Pivot Tables` `Advanced Formulas` `Data Visualization`

**What I Learned:** Building professional-grade dashboards with Excel's native features for quick business insights

[**→ View Full Project**](https://github.com/Bassel-allaa/Superstore_Sales_Analysis)

---

### 4️⃣ SQL Job Market Analysis

> **Data-driven exploration of data analyst career landscape**

**Overview:** Queried PostgreSQL database to identify top-paying roles, most in-demand skills, and salary optimization strategies in the data analyst job market.

**Key Insights:**

- Skills like **Tableau, AWS, Azure** linked to higher compensation
- Remote opportunities analyzed for location flexibility
- **SQL, Python, Tableau** identified as essential skill trio

**Technologies:** `SQL` `PostgreSQL` `CTEs` `Joins` `Aggregations`

**What I Learned:** Complex query optimization and real-world application of SQL for strategic career insights

[**→ View Full Project**](https://github.com/Bassel-allaa/SQL_Project_Data_Job_Analysis)

---

### 5️⃣ Power BI Dashboards

> **Collection of interactive business intelligence visualizations**

[![Power BI Dashboard](https://github.com/Bassel-allaa/Bassels_Data_Analyst_Portfolio/raw/main/images/Project1_Dashboard_Overview.gif)](/Bassel-allaa/Bassels_Data_Analyst_Portfolio/blob/main/images/Project1_Dashboard_Overview.gif)

**Overview:** Portfolio of Power BI dashboards demonstrating data modeling, DAX calculations, and interactive visualization techniques across various business scenarios.

**Key Features:**

- Dynamic KPI tracking with drill-down capabilities
- Trend analysis with time-intelligence functions
- Interactive filters for multi-dimensional analysis

**Technologies:** `Power BI` `DAX` `Data Modeling` `ETL`

**What I Learned:** Advanced visualization techniques and creating user-friendly analytical interfaces

[**→ View Full Project**](https://github.com/Bassel-allaa/Power_BI_Dashboards)

---

### 6️⃣ Excel Salary Analytics

> **Comprehensive analysis of data professional compensation and skills**

[![Excel Salary Dashboard](https://github.com/Bassel-allaa/Bassels_Data_Analyst_Portfolio/raw/main/images/Salary_analysis.png)](/Bassel-allaa/Bassels_Data_Analyst_Portfolio/blob/main/images/Salary_analysis.png)

**Overview:** Dual-component project featuring a salary exploration dashboard for job seekers and skills analysis examining what top employers seek in data professionals.

**Key Components:**

- **Salary Dashboard:** Interactive tool for exploring compensation by role, location, and experience
- **Skills Analysis:** Mapping of in-demand skills to salary potential

**Technologies:** `Excel` `Dashboard Design` `Statistical Analysis`

**What I Learned:** Creating practical, career-oriented analytical tools that directly support decision-making

[**→ View Full Project**](https://github.com/Bassel-allaa/Excel_Project-Data_Analytics)

---

## Technical Skills

| Data Analysis & Querying | Visualization & BI |
|---|---|
| **SQL/PostgreSQL** - Complex queries, CTEs, window functions | **Power BI** - DAX, data modeling, interactive dashboards |
| **Python** - Pandas, NumPy, web scraping, regression modeling with scikit-learn | **Excel Dashboards** - Charts, conditional formatting, UX design |
| **Excel** - Advanced formulas, pivot tables, data modeling | **Data Storytelling** - Translating insights for stakeholders |
| **Data Cleaning** - ETL processes, data validation, fuzzy deduplication | **Matplotlib/Seaborn** - Custom-themed exploratory visualization |
| **Statistical Analysis** - Trend analysis, forecasting, model evaluation | |

---

## What's Next

I'm continuously expanding my analytical toolkit and building new projects:

- **In Progress:** Adding trim-level features to the UAE car pricing model
- **Planned:** Predictive analytics for sales forecasting using machine learning
- **Upcoming:** Tableau certification and advanced visualization projects
- **Learning:** dbt and analytics engineering fundamentals

---

## About Me

I'm a Google-certified data analyst looking for my first full-time role. I've spent the last several months building a portfolio of projects that demonstrate I can handle real data analysis work — from database design and SQL queries to a full self-scraped Python pipeline with regression modeling.

**What I Bring:**

- **Python:** Web scraping, pandas-based data pipelines, regression modeling with scikit-learn, and honest model evaluation
- **Advanced SQL:** CTEs, window functions, joins, data modeling — comfortable with complex queries
- **Power BI:** Interactive dashboards with proper data modeling and DAX
- **Excel:** Pivot tables, advanced formulas, dashboard design
- **Business thinking:** I don't just analyze data; I think about what it means for the business

**My Best Work:** The UAE Used Car Market Analysis is where I'm most proud. I scraped 28K+ real listings from three different marketplaces myself — no Kaggle download — worked through real bugs along the way (a silent encoding issue, a misread API structure), built regression models, and when the first version of my pricing model gave a miscalibrated result, I dug into *why* instead of just reporting the number. If you want to see what I can actually do, start there.

**What I'm After:** An entry-level data analyst position where I can:

- Write SQL and Python daily (I genuinely enjoy both)
- Build dashboards and pipelines that drive decisions
- Learn from experienced analysts
- Contribute to real business problems

**The Honest Truth:** I'm early in my career, but I'm not starting from zero. I've put in the hours to learn the tools, build the projects, and develop the mindset of an analyst. I'm looking for a team that values drive and aptitude over years of experience.

**Beyond Work:** I believe in building in public, which is why this portfolio exists.

---

## Project Showcase

### Sample Dashboards & Visualizations

- [Sales Dashboard](/Bassel-allaa/Bassels_Data_Analyst_Portfolio/blob/main/images/dashboard_overview.png) *Interactive Sales Performance Dashboard*
- [Analytics Dashboard](/Bassel-allaa/Bassels_Data_Analyst_Portfolio/blob/main/images/Project1_Dashboard_Overview.gif) *E-Commerce Analytics Overview*
- [Excel Dashboard](/Bassel-allaa/Bassels_Data_Analyst_Portfolio/blob/main/images/Salary_analysis.png) *Excel-Based Reporting System*
- [SQL Analysis](/Bassel-allaa/Bassels_Data_Analyst_Portfolio/blob/main/images/skill_analysis.png) *SQL Query Results & Insights*

---

## Project Repository Structure

Each project repository includes:

- **README.md** - Project overview, objectives, and key findings
- **Data files** - Sample datasets or links to data sources
- **Code/Queries** - SQL scripts, Excel files, Power BI files, or Python notebooks
- **Visualizations** - Dashboard screenshots and charts
- **Documentation** - Analysis methodology and insights

---

## Certification

- Foundations of Data Science (Google — Issued Nov 2025, Credential ID BC2DZHB9FBWL)
- Google Data Analytics Specialization (Google — Issued Apr 2025, Credential ID HCLITJRMBNN6)
- Data Analysis with R Programming (Google — Issued Dec 2024, Credential ID D0U64PUZJGDY)
- Share Data Through the Art of Visualization (Google — Issued Dec 2024, Credential ID 30Y4NHP92650)
- Analyze Data to Answer Questions (Google — Issued Dec 2024, Credential ID D5ZYP8SP8XW9)
- Process Data from Dirty to Clean (Google — Issued Nov 2024, Credential ID XJZRZZQE9FND)
- Prepare Data for Exploration (Google — Issued Nov 2024, Credential ID J0NUMD8DEEZT)
- Ask Questions to Make Data-Driven Decisions (Google — Issued Nov 2024, Credential ID J0TR1XAIMHTP)
- Foundations: Data, Data, Everywhere (Google — Issued Nov 2024, Credential ID WTK491RPYT79)

## Let's Connect

I'm actively seeking opportunities and open to collaboration!

**Email:** basel3la2@gmail.com

**Phone Number:** +201555552197

[**LinkedIn**](https://www.linkedin.com/in/bassel-elseadawy-675414339/)

[**GitHub**](https://github.com/Bassel-allaa)

**Portfolio Site:** *Coming Soon*

---

## Support This Portfolio

If you find these projects helpful or inspiring:

- **Star this repository** to show your support
- **Share** with others who might benefit
- **Reach out** with feedback or collaboration ideas

---

## License

This portfolio and its contents are available under the [MIT License](https://github.com/Bassel-allaa/Bassels_Data_Analyst_Portfolio/blob/main/LICENSE).

---

**Built with data, coffee, and curiosity**

*Last Updated: July 2026*
