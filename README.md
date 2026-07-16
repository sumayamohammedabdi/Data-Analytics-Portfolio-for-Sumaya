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
- **[Project 6 — Pandas](#project-6--pandas)**
- **[Project 7 — Python](#project-7--python)**
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
- Using `=MAX()` to find the highest score per student
- Applying conditional formatting to highlight the highest and lowest averages
- Building a pivot table from the Bike Sales dataset
- Using the SWITCH/IF function to categorise sales volume into High, Medium, and Low

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

### Output — Filter Applied: Best Students per Subject

![Best Students Filter](Images/Excel/image5.png)

*Filter and sort applied to show top performing students in each subject.*

---

### Output — Pivot Table: Bike Sales by County and Product

![Bike Sales Pivot](Images/Excel/image10.png)

*Pivot table summarising bike sales volume by county and product type.*

---

### Output — SWITCH Function: Sales Volume Category

![Switch Function](Images/Excel/image11.png)

*SWITCH/IF formula applied to categorise sales as High, Medium, or Low based on volume thresholds.*

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

### Output — Life Expectancy by Continent

![Life Expectancy Continent](Images/Tableau_PowerBI/image4.png)

*Bar chart showing average life expectancy by continent using the GapminderHealth dataset.*

---

### Output — Life Expectancy Trend Over Time

![Life Expectancy Trend](Images/Tableau_PowerBI/image5.png)

*Line chart showing life expectancy trends for the top 5 countries over time.*

---

### Output — Population Distribution by Gender

![Population Gender](Images/Tableau_PowerBI/image6.png)

*Pie chart showing population distribution by gender for a selected country and year.*

---

### Output — BMI vs Life Expectancy

![BMI Life Expectancy](Images/Tableau_PowerBI/image7.png)

*Scatter plot showing the relationship between BMI and life expectancy across countries.*

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

### Output — Profit Page

![Power BI Profit](Images/Tableau_PowerBI/image14.png)

*Profit analysis page showing revenue, cost, and margin trends by year and category.*

---

### Output — My Performance Page

![Power BI Performance](Images/Tableau_PowerBI/image15.png)

*Individual salesperson performance page filtered by name with dynamic slicer.*

---

### Output — Table Relationships in Model View

![Power BI Relationships](Images/Tableau_PowerBI/image16.png)

*Data model showing table relationships created between fact and dimension tables.*

---

### Output — Power Query Data Cleaning

![Power BI Power Query](Images/Tableau_PowerBI/image17.png)

*Power Query editor showing data cleaning steps applied before loading to the model.*

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

### Output — SQL JOIN Types Research

![SQL Joins](Images/SQL/image6.png)

*Research task documenting all six JOIN types with diagrams and examples.*

---

### Output — SQL Practical Queries — Filtering

![SQL Filtering](Images/SQL/image10.png)

*SQL queries using WHERE, IN, BETWEEN, and NOT BETWEEN to filter records.*

---

### Output — SQL Practical Queries — GROUP BY and Aggregation

![SQL Grouping](Images/SQL/image11.png)

*SQL queries using GROUP BY, COUNT, AVG, and SUM to summarise data.*

---

### Output — SQL CASE Statement

![SQL CASE](Images/SQL/image12.png)

*CASE statement used to create age brackets and performance categories in SQL.*

---

### Output — SQL CREATE TABLE

![SQL Create Table](Images/SQL/image23.png)

*CREATE TABLE statement defining a student scoring table with correct data types.*

---

## Project 5 — Azure

[↟ Back to Table of Contents](#table-of-contents)

### Problem

Research and recommend a Microsoft Azure cloud migration strategy for a small business. Tasks covered cloud models, data laws, Azure services, storage formats, data modelling, and cost estimation.

### Approach Taken

Recommended Azure services for a pet shop (Paws & Whiskers) migrating from spreadsheets to the cloud. Designed a relational data model.

### Insights

- Azure SQL Database and Blob Storage together cover all structured and unstructured data needs
- Azure Data Factory automates ETL pipelines removing the need for manual data entry
- GDPR and DPA 2018 require data minimisation, encryption, and breach reporting within 72 hours
- Azure UK South region satisfies UK data residency requirements for GDPR compliance

### Impact

- Replaces unreliable manual spreadsheets with a secure cloud database
- Provides automated data pipelines and real-time Power BI dashboards
- Meets GDPR, DPA 2018, and PCI DSS compliance requirements
- Delivers a scalable architecture that grows with the business

---

### Output — Paws and Whiskers Cloud Proposal

![Azure Proposal](Images/Azure/image20.png)

*Cloud migration proposal for Paws and Whiskers covering Azure services and data modelling.*

---

## Project 6 — Pandas

[↟ Back to Table of Contents](#table-of-contents)

### Dataset

student_in_.csv — 35 students, 5 columns (id, name, class, mark, gender)

### Problem

Load, explore, slice, manipulate, aggregate, and export the student dataset using Pandas in Google Colab.

### Approach Taken

Used `read_csv`, `head`, `info`, `describe`, `iloc`, `groupby`, `pivot_table`, `apply`, `sort_values`, and `to_csv` to fully analyse and export the dataset. Created a custom grade function and applied it across the DataFrame.

### Insights

- Class Six had the highest average score (82.57)
- Class Four had the lowest average score (68.75)
- Female students averaged slightly higher than males (77.3 vs 71.6)
- Top student: Kenn Rein — score 96, Class Six, Female, Grade A
- Lowest score: 18 (Class Nine)

### Impact

- Demonstrates a complete end-to-end Pandas workflow from loading to export
- Pivot table and groupby outputs directly mirror Excel analysis for validation
- Custom grade function demonstrates use of apply() for conditional column creation
- Exported CSV is ready for database ingestion or further BI reporting

---

### Output — DataFrame Head and Info

![Pandas Head](Images/Python/image2.png)

*First rows of the student DataFrame loaded from CSV, showing all columns and data types.*

---

### Output — Groupby: Average Score per Class

![Pandas Groupby](Images/Python/image4.png)

*Groupby query showing average score per class — Class Six leads, Class Four lowest.*

---

### Output — Pivot Table

![Pandas Pivot](Images/Python/image9.png)

*Pivot table showing average student scores broken down by class and gender.*

---

### Output — Grade Column Applied

![Pandas Grade](Images/Python/image12.png)

*Custom grade function applied to the score column — A, B, C, D assigned per student.*

---

### Output — Sorted DataFrame

![Pandas Sorted](Images/Python/image18.png)

*DataFrame sorted by score descending — Kenn Rein at the top with score 96.*

---

### Output — GDP Dataset: First 10 Rows

![GDP Head](Images/Python/image20.png)

*First 10 rows of the GDP (nominal) per Capita dataset loaded from CSV — 223 countries.*

---

## Project 7 — Python

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

### Output — Box Plot: Score Distribution

![Box Plot](Images/Python/image24.png)

*Box and whisker plot showing score distribution and outliers across all classes.*

---

### Output — GDP Dataset Analysis

![GDP Analysis](Images/Python/image25.png)

*Pandas analysis of the GDP dataset showing regional filtering and top 10 wealthiest countries.*

---

### Output — GDP Bar Chart by Region

![GDP Bar Chart](Images/Python/image26.png)

*Bar chart showing average IMF GDP estimate per region — Europe leads, Africa lowest.*

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

