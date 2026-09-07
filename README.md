# Customer_product_behavior_analysis
ustomer Shopping Behavior Analysis
End-to-End Data Analytics Portfolio Project
Python | Pandas | PostgreSQL | SQL | Power BI | Gamma
Overview
This project presents an end-to-end analysis of customer shopping behavior, with a focus on uncovering actionable
insights related to purchasing patterns, customer loyalty, product performance, discount usage, and subscription
behavior.
Using Python and Pandas, I performed exploratory data analysis (EDA), data cleaning, and transformation to prepare
the dataset for analysis. The cleaned data was then integrated into PostgreSQL, where I developed SQL queries to
answer key business questions, including customer segmentation, revenue contribution, repeat purchasing behavior,
product performance, and the relationship between discounts and spending.
To translate the analysis into clear, decision-ready insights, I developed an interactive Power BI dashboard highlighting
key performance indicators and customer trends. The project concludes with a structured business report and
presentation summarizing the findings and their potential business implications.
This project demonstrates my ability to manage the full data analytics lifecycle - from raw data preparation and SQL
analysis to data visualization and business storytelling - while translating data into insights that can support
informed business decisions.
Business Objective
The objective of this project is to analyze customer purchasing behavior and identify patterns that could help a business
better understand its customers and make more informed decisions.
• Which customer groups contribute the most revenue?
• How does subscription status relate to customer spending?
• Which products receive the highest customer ratings?
• Which products are purchased most frequently within each category?
• How frequently are discounts used across different products?
• How do repeat customers compare with other customer segments?
• How does revenue vary across customer age groups?
• Does shipping preference relate to average customer spending?
Dataset
The dataset contains customer-level shopping and transaction information used to analyze purchasing behavior across
multiple customer and product dimensions.
• Customer ID, age, and gender
• Item purchased and product category
• Purchase amount and location
Customer Shopping Behavior Analysis | Page 2
• Size, color, and season
• Review rating and subscription status
• Shipping type and discount applied
• Previous purchases, payment method, and purchase frequency
The dataset was first explored and cleaned in Python before being transferred to PostgreSQL for SQL-based business
analysis.
Tools & Technologies
Tool Purpose
Python Data preparation and analysis
Pandas Data cleaning, transformation, and exploratory analysis
Jupyter Notebook Python development and documentation
PostgreSQL Database management and SQL analysis
SQL Aggregation, segmentation, ranking, and business analysis
Power BI Interactive dashboard development and visualization
Gamma Presentation development
GitHub Project documentation and version control
Project Workflow
1. Data Loading & Initial Exploration
The dataset was imported into a Jupyter Notebook using Pandas. Initial exploratory analysis was performed using
methods such as head(), info(), describe(), and isnull().sum() to understand the structure and quality of the data.
• Reviewed dataset dimensions, columns, and data types
• Examined descriptive statistics and categorical variables
• Identified missing values and potential data-quality issues
2. Exploratory Data Analysis (EDA)
EDA was performed to understand customer characteristics and purchasing behavior before conducting deeper SQL
analysis. This stage established the foundation for determining which transformations were necessary before loading the
data into the database.
3. Data Cleaning & Transformation
The dataset was cleaned and transformed using Python and Pandas to improve data quality and prepare it for analysis.
• Handled missing review ratings using the median rating within each product category
• Standardized column names by converting them to lowercase and replacing spaces with underscores
• Created customer age groups for demographic analysis
Customer Shopping Behavior Analysis | Page 3
• Converted purchase-frequency categories into estimated numerical day values
• Reviewed related discount and promotional fields and removed redundant information
Using the category-level median for missing review ratings helped preserve differences in rating patterns across product
categories rather than applying one value to the entire dataset.
4. PostgreSQL Integration
After cleaning and transforming the data, the prepared DataFrame was loaded into PostgreSQL for structured SQL
analysis. This created a practical analytics workflow:
Raw Dataset -> Python -> Data Cleaning -> PostgreSQL -> SQL Analysis -> Power BI
5. SQL Business Analysis
SQL queries were developed to answer business-focused questions related to customers, revenue, products, discounts,
subscriptions, and purchasing behavior.
• Total revenue generated by male vs. female customers
• Customers who used a discount but still spent at or above the average purchase amount
• Top five products with the highest average review ratings
• Average purchase amounts for Standard vs. Express Shipping
• Subscriber vs. non-subscriber customer count, average spend, and total revenue
• Five products with the highest percentage of discounted purchases
• Customer segmentation into New, Returning, and Loyal groups
• Top three most purchased products within each category
• Relationship between repeat buyers and subscription status
• Revenue contribution by age group
SQL Techniques Demonstrated
• SELECT, WHERE, GROUP BY, and ORDER BY
• SUM(), AVG(), and COUNT() aggregate functions
• Subqueries and conditional aggregation
• CASE WHEN logic
• Common Table Expressions (CTEs)
• ROW_NUMBER() and PARTITION BY window functions
• Customer segmentation, filtering, ranking, and comparison
6. Power BI Dashboard
An interactive Power BI dashboard was developed to present the findings in a clear, business-friendly format. The
dashboard brings together key customer and purchasing metrics so stakeholders can identify trends without reviewing
individual SQL queries or raw data.
• Revenue performance
• Customer purchasing behavior and demographics
Customer Shopping Behavior Analysis | Page 4
• Product and category performance
• Subscription behavior and discount usage
• Customer segments and purchasing trends
Business Insights
The analysis was designed to provide a more complete understanding of customer shopping behavior across several
areas of the business.
• Customer Revenue: Compared customer groups to understand differences in revenue contribution.
• Customer Loyalty: Used previous purchasing activity to distinguish new, returning, loyal, and repeat customers.
• Subscription Behavior: Compared subscribers and non-subscribers by customer count, average spending, and total
revenue.
• Product Performance: Evaluated purchase frequency and customer review ratings to identify stronger-performing
products.
• Discount Behavior: Analyzed discount usage and identified discounted transactions that still generated
above-average purchase values.
• Customer Demographics: Examined revenue contribution across engineered age groups.
These analyses can support decisions related to customer retention, product strategy, promotional planning, subscription
programs, and customer targeting.
Report & Presentation
The findings were organized into a structured business report and a presentation created using Gamma. These
deliverables communicate the analytical process, findings, and business implications in formats suitable for both
technical and non-technical stakeholders.
Project Deliverables
• Jupyter Notebook: Data loading, EDA, cleaning, transformation, feature engineering, and database integration
• SQL Script: Business questions and SQL analysis
• Power BI Dashboard: Interactive visualization of customer shopping behavior
• Business Report: Analysis methodology, findings, and insights
• Gamma Presentation: Stakeholder-focused presentation of findings
• README: Complete project documentation
How to Run the Project
• 1. Clone or download the GitHub repository.
• 2. Install the required Python libraries, including pandas, SQLAlchemy, and psycopg2-binary.
• 3. Open the Jupyter Notebook and run the cells in sequence to load, explore, clean, and transform the data.
• 4. Create a PostgreSQL database and configure the connection using local credentials.
• 5. Load the cleaned dataset into PostgreSQL and execute the SQL analysis against the customer table.
Customer Shopping Behavior Analysis | Page 5
• 6. Open the Power BI .pbix file in Power BI Desktop to explore the dashboard.
Security Note: Database usernames, passwords, API keys, and other credentials should never be committed to a public
GitHub repository. Store sensitive credentials in environment variables or an excluded .env file.
Skills Demonstrated
• Exploratory Data Analysis (EDA)
• Data Cleaning and Data Transformation
• Feature Engineering and Customer Segmentation
• Python, Pandas, and Jupyter Notebook
• PostgreSQL and SQL
• Subqueries, CTEs, CASE statements, conditional aggregation, and window functions
• Power BI dashboard development and KPI analysis
• Data Visualization and Data Storytelling
• Business Analysis and Insight Communication
Conclusion
This project demonstrates an end-to-end data analytics workflow, beginning with raw customer data and progressing
through data exploration, cleaning, transformation, database integration, SQL analysis, visualization, and business
communication.
By combining Python, Pandas, PostgreSQL, SQL, and Power BI, I transformed customer shopping data into
structured business insights related to customer behavior, loyalty, product performance, subscriptions, discounts, and
revenue.
Most importantly, the project demonstrates the ability to connect technical analysis with business objectives - using data
not only to answer analytical questions, but also to communicate findings in a way that can support informed
