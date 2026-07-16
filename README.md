# Sumaya Abdi | Data Analytics Portfolio

Hi, I am **Sumaya Abdi**, a Data Technician Trainee building practical projects using Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python.

This GitHub Pages site showcases all my projects, including screenshots, visualisations, and analysis tasks.

---

## Table of Contents

- **[Project 1 — Excel](#project-1--excel)**
- **[Project 2 — Tableau](#project-2--tableau)**
- **[Project 3 — Power BI](#project-3--power-bi)**
- **[Project 4 — SQL](#project-4--sql)**
- **[Project 5 — Azure](#project-5--azure)**
- **[Project 6 — Python](#project-7--python)**
- **[Final Summary](#final-summary)**
- **[Socials](#socials)**

*Click the links to jump to each section.*

---

## Portfolio Projects

---

## Project 1 — Excel

[↟ Back to Table of Contents](#table-of-contents)

### Problem

Using the retail sales dataset and student grades dataset, I analysed and structured data by:

- Converting raw data into named Excel tables using Ctrl+T
- Applying filters and sorting to find the best students per subject
- Using `=SUM()` and `=AVERAGE()` to calculate totals and averages
- Applying conditional formatting to highlight the highest and lowest averages
- Building a pivot table from the Bike Sales dataset

### Approach Taken

Imported and cleaned raw datasets, applied Excel formulas across all rows, used conditional formatting to make results immediately visual, built pivot tables to summarise sales by county and product, and used SWITCH logic to categorise performance.

### Insights

- Best student overall by average: Carol (81.67)
- Best student by highest individual score: Linda (90)
- Class Six had the strongest average in the Bike Sales dataset
- Cornwall and Essex led with the highest sales volumes (1100 each — High category)

### Impact

- Supports targeted academic interventions for underperforming students
- Enables sales teams to identify high and low performing regions instantly
- Pivot table provides a reusable structure for future schedule analysis

---

### Output — Retail Sales Table

![Excel Retail Sales](Images/Excel/image1.png)

*Retail sales dataset converted to a named Excel table with filters applied.*

---

### Output — Student Grades with Average and Highest Score

![Student Grades](Images/Excel/image2.png)

*Student grades table showing calculated averages and highest scores using =AVERAGE() and =MAX().*

---

### Output — Conditional Formatting Applied

![Conditional Formatting](Images/Excel/image3.png)

*Conditional formatting applied to average scores — green highlights highest, red highlights lowest.*

---

### Output — Pivot Table: Bike Sales by County and Product

![Bike Sales Pivot](Images/Excel/image10.png)

*Pivot table summarising bike sales volume by county and product type.*

---

### Output — SUM and AVERAGE in Retail Dataset

![Sum Average](Images/Excel/image12.png)

*SUM and AVERAGE formulas applied to the commission column of the retail sales dataset.*

---

## Project 2 — Tableau

[↟ Back to Table of Contents](#table-of-contents)

### Problem

Using Tableau and the GapminderHealth dataset I created visualisations to explore global health trends for a global health organisation.

### Approach Taken

Connected the dataset in Tableau, checked data types, built multiple worksheets covering life expectancy, population, and BMI, and combined them into an interactive dashboard titled **Global Health Insights**.

### Insights

- Europe and Oceania have the highest life expectancy; Africa the lowest
- Life expectancy has steadily increased over time across all continents
- Countries with healthier BMI levels tend to have higher life expectancy
- Population distribution by gender is generally balanced globally

### Impact

- Plan future healthcare demand by continent
- Target public health campaigns in lower-performing regions
- Benchmark country performance against global averages
- Allocate resources based on population density and gender distribution


---

### Output — Global Health Insights Dashboard

![Tableau Dashboard](Images/Tableau_PowerBI/image8.png)

*Final Tableau dashboard combining all four visualisations into one interactive view.*

---

## Project 3 — Power BI

[↟ Back to Table of Contents](#table-of-contents)

### Problem

Build an interactive Power BI dashboard to analyse retail sales performance, identify trends, and provide dynamic insights across categories, regions, and time periods.

### Approach Taken

- Loaded and cleaned data in Power Query
- Created relationships between tables using primary and foreign keys
- Built interactive visuals including bar charts, line charts, and KPI cards
- Added Year and Salesperson slicers connected to all visuals
- Designed a three-page dashboard: Overview, Profit, and My Performance
- Inserted company logo and formatted for a professional business presentation

### Insights

- Clear category performance differences visible across product lines
- Regional sales trends highlight strengths and areas for improvement
- Salesperson performance varies significantly across the team
- Slicer filtering enables rapid year-on-year comparison

### Impact

- Enables management to make faster data-driven decisions
- Highlights underperforming regions and categories for targeted action
- Supports individual performance reviews with evidence-based filtering
- Provides a scalable template for ongoing monthly reporting

---

### Output — Power BI Overview Dashboard

![Power BI Overview](Images/Tableau_PowerBI/image13.png)

*Interactive overview dashboard showing KPIs, category breakdowns, and regional performance.*
---

## Project 4 — SQL

[↟ Back to Table of Contents](#table-of-contents)

### Problem

Design and query relational databases using SQL. Tasks included writing JOIN queries, creating tables, filtering data, and analysing results using DB Browser for SQLite.

### Approach Taken

Researched database concepts including primary keys, foreign keys, entity relationships, and JOIN types. Created an ERD diagram. Wrote SQL queries to filter, aggregate, and join tables using real datasets.

### Insights

- Inner joins only return matched rows — essential for linking related tables cleanly
- CASE statements replicate Excel IF logic directly inside SQL queries
- Filtering with IN, BETWEEN, and NOT is faster than multiple OR conditions
- GROUP BY with COUNT and AVG enables instant aggregated business reporting

### Impact

- Provides a reusable SQL query library for data analysis tasks
- ERD design demonstrates understanding of relational database structure
- Query examples cover filtering, grouping, joining, and categorisation
- Directly transferable to real business database environments

---

### Output — Entity Relationship Diagram (ERD)

![ERD Diagram](Images/SQL/image1.png)

*Entity Relationship Diagram showing table entities, attributes, primary keys, and relationships.*

---

### Output — SQL Practical Queries — Filtering

![SQL Filtering](Images/SQL/image10.png)

*SQL queries using WHERE, IN, BETWEEN, and NOT BETWEEN to filter records.*









---



## Project 6 — Python

[↟ Back to Table of Contents](#table-of-contents)

### Dataset

GDP (nominal) per Capita.csv and student_in_.csv

### Problem

Load datasets, write Python programs using loops and functions, create visualisations, and interpret insights using Pandas, Matplotlib, and Seaborn.

### Approach Taken

Wrote FizzBuzz using a for loop and modulus operator. Used `plt.figure`, `sns.barplot`, `sns.boxplot`, and `sns.countplot` to create and interpret charts from both datasets.

### Insights

- FizzBuzz: fizzbuzz appears at multiples of both 3 and 5 (15, 30, 45, 60, 75, 90)
- Class Six is the strongest class; Class Nine the weakest
- Female students score more A grades than males
- Europe leads all regions in average GDP per capita
- Africa has the most countries (55) but the lowest average GDP

### Impact

- FizzBuzz demonstrates loop logic and conditional branching — a core interview skill
- Bar charts and box plots make data patterns immediately communicable
- GDP visualisation demonstrates ability to work with real-world international datasets
- All code is reproducible in Google Colab — ready to share as a notebook

---

### Output — FizzBuzz Code and Output

![FizzBuzz](Images/Python/image21.png)

*FizzBuzz written in Python using a for loop, modulus operator, and if/elif/else logic.*

---

### Output — Bar Chart: Average Score by Class

![Bar Chart](Images/Python/image23.png)

*Seaborn bar chart showing average student score per class from the student dataset.*

---

## Final Summary

[↟ Back to Table of Contents](#table-of-contents)

This data analytics portfolio reflects a broad and practical skill set across Excel, Tableau, Power BI, SQL, Azure, Pandas, and Python. The projects demonstrate structured analytical workflows, effective data visualisation, relational database design, and cloud-based data strategy. I am seeking opportunities where I can apply these skills to deliver meaningful analytical value.

---

## Socials

[↟ Back to Table of Contents](#table-of-contents)

- **Email:** sumayaenow@gmail.com
- **GitHub:** [github.com/sumayaabdi](https://github.com/sumayaabdi)

---

*Portfolio by Sumaya Abdi | Birmingham, UK*  
*Built with GitHub Pages*

