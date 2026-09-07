# Customer_product_behavior_analysis

This project is an end-to-end analysis of customer shopping behavior designed to uncover actionable insights into **purchasing patterns, customer loyalty, product performance, subscription behavior, discount usage, and revenue trends**.

Using **Python and Pandas**, I performed exploratory data analysis (EDA), data cleaning, and transformation to prepare the dataset for analysis. The cleaned data was then loaded into **PostgreSQL**, where I used SQL to answer key business questions related to customer segmentation, revenue performance, repeat purchasing behavior, product rankings, and subscriptions.

The findings were translated into an interactive **Power BI dashboard** and summarized in a business report and presentation, demonstrating the complete analytics workflow from **raw data to decision-ready insights**.

## Business Objective

The objective of this project was to transform customer transaction data into meaningful business insights that could support decisions related to **customer retention, product strategy, marketing, promotions, and subscription growth**.

Key questions explored included:

* Which customer segments contribute the most revenue?
* Do subscribers demonstrate different spending behavior than non-subscribers?
* Which products perform best based on purchases and customer ratings?
* Which products have the highest discount usage?
* Are repeat customers more likely to subscribe?
* How does revenue vary across customer age groups?
* How do purchasing patterns differ by shipping method?

---

## Tools & Technologies

| Tool                 | Purpose                                      |
| -------------------- | -------------------------------------------- |
| **Python**           | Data analysis and preparation                |
| **Pandas**           | Data cleaning, transformation, and EDA       |
| **Jupyter Notebook** | Analysis and development environment         |
| **PostgreSQL**       | Database management                          |
| **SQL**              | Business analysis and customer segmentation  |
| **Power BI**         | Dashboard development and data visualization |
| **Gamma**            | Business presentation                        |
| **GitHub**           | Project documentation and version control    |

---

## Project Workflow

### 1. Data Exploration

Loaded the customer shopping dataset into Python and performed exploratory data analysis to understand the structure, distributions, data types, and overall data quality.

Key methods included:

`head()` • `info()` • `describe()` • `isnull().sum()`

### 2. Data Cleaning & Transformation

Prepared the dataset for analysis by:

* Identifying and handling missing values
* Filling missing review ratings using the **median rating within each product category**
* Standardizing column names
* Creating customer **age groups**
* Transforming purchase-frequency categories into numerical values
* Identifying and removing redundant information

### 3. PostgreSQL Integration

Loaded the cleaned dataset into **PostgreSQL** to create a structured environment for business analysis.

**Data Pipeline:**

`Raw Dataset → Python/Pandas → Cleaned Data → PostgreSQL → SQL Analysis → Power BI`

### 4. SQL Analysis

Developed **10 business-focused SQL queries** to analyze customer behavior and purchasing trends.

The analysis covered:

* Revenue by customer demographic
* Above-average spending among discount users
* Highest-rated products
* Shipping method spending comparison
* Subscriber vs. non-subscriber performance
* Product discount rates
* Customer segmentation
* Top products within each category
* Repeat buyer subscription behavior
* Revenue contribution by age group

SQL techniques demonstrated include:

`GROUP BY` • `SUM()` • `AVG()` • `COUNT()` • `CASE WHEN` • Subqueries • CTEs • Conditional Aggregation • `ROW_NUMBER()` • `PARTITION BY`

### 5. Power BI Dashboard

Developed an interactive **Power BI dashboard** to transform the analysis into a clear visual summary of customer and business performance.

The dashboard highlights:

* Revenue and sales performance
* Customer demographics
* Product and category performance
* Subscription behavior
* Customer segments
* Discount usage
* Purchasing patterns

### 6. Reporting & Presentation

Summarized the analytical process, findings, and business implications in a structured report and created a **Gamma presentation** to communicate the results in a stakeholder-friendly format.

---

## Key Business Insights

The analysis provides visibility into several important areas of customer behavior:

* **Customer Segmentation:** Identified New, Returning, and Loyal customer groups based on previous purchasing activity.
* **Subscription Analysis:** Compared subscriber and non-subscriber behavior using customer count, average spend, and total revenue.
* **Product Performance:** Identified highly rated and frequently purchased products across categories.
* **Discount Analysis:** Evaluated which products rely most heavily on discounted purchases.
* **Customer Demographics:** Analyzed revenue contribution across different age groups.
* **Repeat Purchasing:** Examined the relationship between repeat purchasing behavior and subscription status.

These insights can support more informed decisions around **customer retention, targeted marketing, promotional strategy, product positioning, and subscription programs**.

---

## Project Deliverables

* **Jupyter Notebook** — EDA, data cleaning, transformation, and database integration
* **SQL Script** — 10 business-focused analytical queries
* **Power BI Dashboard** — Interactive customer behavior dashboard
* **Business Report** — Findings and business insights
* **Gamma Presentation** — Stakeholder-focused project presentation

---

## Skills Demonstrated

**Python • Pandas • Exploratory Data Analysis • Data Cleaning • Data Transformation • Feature Engineering • PostgreSQL • SQL • CTEs • Subqueries • Window Functions • Customer Segmentation • Power BI • Data Visualization • Business Intelligence • Data Storytelling**

---

## Conclusion

This project demonstrates my ability to execute an **end-to-end data analytics workflow**, from preparing and analyzing raw data to developing SQL-driven business insights and communicating results through an interactive dashboard.

By combining **Python, PostgreSQL, SQL, and Power BI**, I transformed customer shopping data into clear, business-focused insights that can support more informed decisions around **customers, products, revenue, and retention**.
