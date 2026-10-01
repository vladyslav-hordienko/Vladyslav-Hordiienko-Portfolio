# Vladyslav-Hordiienko-Portfolio

Vladyslav Hordiienko - Data Analyst

---

# Featured Projects

## [Sales & Traffic Analysis](https://colab.research.google.com/drive/1hOoHGm3nnuUyAwyKzxi3VSY3nRgIL4F8?usp=sharing)

This end-to-end data analytics project focuses on sales performance, customer behavior, and key business trends. Data was extracted from multiple tables in **Google BigQuery using SQL**, combining information about sessions, orders, products, users, geographic locations, devices, and traffic sources into a single dataset. The prepared data was then loaded into Python for further processing and analysis.

Using **Python, Pandas, NumPy, Matplotlib, and Seaborn**, the project included data exploration, missing-value analysis, aggregations, pivot tables, and visualization. Sales were analyzed across continents, countries, product categories, device types, and traffic channels. The analysis also covered sales dynamics over time, regional differences, customer registration and subscription behavior, and relationships between traffic and sales performance.

The project included **statistical analysis** to examine correlations between sales, sessions, regions, traffic channels, and product categories. I used statistical significance and hypothesis testing to evaluate relationships between metrics and differences between customer and traffic groups. The results were supported by Python visualizations and conclusions based on the identified patterns.

The final insights were presented through an **interactive Tableau dashboard**, providing a clear overview of the main business metrics and findings.

**Tools:** SQL, Google BigQuery, Python, Pandas, NumPy, Matplotlib, Seaborn, Tableau

Tableau Dashboard: https://www.google.com/url?q=https%3A%2F%2Fpublic.tableau.com%2Fapp%2Fprofile%2Fvladyslav.hordiienko7457%2Fviz%2FSalesTrafficAnalysis%2FSalesPerformanceAnalysis%3Fpublish%3Dyes%240



## [Custom A/B Testing Tool ](https://github.com/jhgjvvjk/Custom-A-B-Testing-Tool)

Reusable A/B testing analysis tool that combines SQL-based data preparation with Tableau visualization. The SQL query collects experiment data for different tests and test groups, together with session attributes such as country, continent, device, and traffic channel.

Several key metrics are prepared for analysis, including total sessions, sessions with orders, new accounts, and user events. Separate CTEs calculate each group of metrics, after which the results are combined into a unified dataset that can be used across multiple A/B tests and different analytical dimensions.

The resulting dataset makes it possible to compare control and test groups across countries, devices, channels, and other segments while tracking conversion-related events throughout the user funnel. The structure is designed to support multiple tests and metrics rather than a single fixed experiment.

The prepared data is then used in Tableau to create an interactive A/B testing dashboard, allowing test results and conversion metrics to be compared visually across test groups and selected filters.

Tools: SQL, Google BigQuery, Tableau

Key Areas: A/B Testing, Conversion Analysis, Data Preparation, CTEs, Aggregations, UNION ALL, Dashboard Visualization

Tableau Dashboard: https://public.tableau.com/app/profile/vladyslav.hordiienko7457/viz/ABTesting_17840399792710/ABTest



## [A/B Testing & Conversion Analysis](https://colab.research.google.com/drive/1HJT2tfbnxYJAg3CA4OANiEeEnwO1HCUt?usp=sharing)

The project analyzes **A/B test results and conversion performance** across four key funnel metrics: adding payment information, adding shipping information, beginning checkout, and creating a new account. The main goal was to compare control and test groups and determine whether observed differences in conversion were statistically significant.

The analysis was performed in **Python using Google Colab**, where conversion rates and statistical significance were calculated for each metric. The calculations were structured to process multiple metrics automatically, allowing the same approach to be applied across different tests rather than analyzing every metric separately.

I prepared the results for visualization and connected them to **Tableau**, where conversion rates, between-group differences, and statistical significance were presented in an interactive dashboard. Test-level filtering makes it possible to compare experiment results and quickly identify metrics where the observed changes are statistically meaningful.

**Tools:** Python, Pandas, Google Colab, A/B Testing, Statistical Analysis, Tableau

Tableau Dashboard:https://public.tableau.com/app/profile/vladyslav.hordiienko7457/viz/ABTestingMetrics/Dashboard2


---

### [SQL Helper](https://github.com/vladyslav-hordienko/SQL_Helper)
Developed a Python-based SQL learning tool for practicing, validating, and troubleshooting SQL queries in a safe local environment. The project includes a synthetic SQLite sales database with customers, orders, products, payments, refunds, and employees to simulate realistic analytics tasks. I implemented SQL parsing and validation with SQLGlot, added read-only query execution for SELECT and WITH statements, and blocked destructive SQL commands to keep the app safe for practice. The web interface allows users to write SQL, view formatted queries, check validation messages, and preview query results. I also added practice tasks, trainer hints for common SQL concepts such as GROUP BY, COUNT, SUM, AVG, JOIN, and filtering, plus an optional OpenAI-powered AI tutor through a backend API with API keys handled through environment variables. The project was prepared as a GitHub-safe portfolio version with documentation, .gitignore, and no secrets, real data, or local environment files.

**Tech stack:** Python, SQLite, SQLGlot, OpenAI API, HTML, CSS, JavaScript

---

# Python Projects

## 📊 [International Sales & Business Performance Analysis](https://colab.research.google.com/drive/1JEo_wYX0JLjrXxHQMzrl09BoALasjPvT?usp=sharing)

A comprehensive sales and business performance analysis completed in Python using Google Colab. The project works with three related datasets containing order, product, and country information, which were cleaned, prepared, transformed, and combined into a single analytical dataset.

The analysis covers the company’s key financial and operational metrics, including **revenue, costs, profit, units sold, order volume, and geographic coverage**. Performance was compared across **product categories, countries, regions, and online/offline sales channels** to identify the strongest markets and products and understand differences between sales volume, revenue, costs, and actual profitability.

The project also explores **shipping and order processing times** across categories and geographic markets and examines whether shipping time has a noticeable relationship with profit. Sales dynamics were analyzed over time by **product category, country, and region**, while day-of-week analysis was used to identify weekly demand patterns and possible changes in customer purchasing behavior.

Country- and region-level comparisons were used to identify the markets contributing the most to revenue, profit, and sales volume. The analysis provides an overall view of the company’s performance and highlights the product categories and markets making the strongest contribution to business results.

**Key Metrics:** $1.70B Total Revenue • $501.4M Total Profit • 6.57M Units Sold • 1,330 Orders • 45 Countries

**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Google Colab

---

# SQL Projects

## [Email & Account Activity Analysis](https://github.com/jhgjvvjk/Email-Account-Activity-Analysis/blob/main/main)

This SQL project analyzes **account activity and email communication performance across different countries and dates**. The query tracks the number of unique accounts together with key email metrics, including **messages sent, opened, and visited**, providing a combined view of user activity and email engagement.

Account data is analyzed by **date, country, sending interval, verification status, and subscription status**. Email activity is processed separately and then combined with account-level metrics into a unified dataset, making it possible to track how account and communication activity changes over time and across different user segments.

The query uses multiple **CTEs, joins, aggregations, UNION ALL, and window functions** to calculate both detailed and country-level metrics. Total numbers of accounts and sent emails are calculated for each country, followed by ranking countries based on their overall account volume and email activity.

The final output identifies the **top 10 countries by number of accounts and email volume**, while preserving daily and account-level attributes for further analysis of geographic performance, email engagement, verification, and subscription behavior.

**Tools:** SQL, Google BigQuery

**Key Techniques:** CTEs, Joins, Aggregations, UNION ALL, Window Functions, DENSE_RANK



## 📊 [Marketing Performance Analysis](https://github.com/jhgjvvjk/Marketing-Revenue-Performance-Analysis)

Analyzed marketing and business performance using SQL and Google BigQuery by combining data from multiple sources into a consolidated daily report.

The project brings together revenue, paid advertising costs, email activity, and customer registrations. It also calculates key email engagement indicators, including open rate and click rate, providing a clear view of how marketing activity and customer engagement relate to overall business performance.

**Key Metrics:** Revenue, Advertising Cost, Emails Sent, Open Rate, Click Rate, Registrations

**Tools:** SQL, Google BigQuery



## 🌍 [Revenue & User Analysis by Continent](https://github.com/jhgjvvjk/Revenue-User-Analysis-by-Continent/tree/main)

Analyzed revenue and user activity across different continents using SQL and Google BigQuery. The analysis compares regional revenue performance and examines how revenue is distributed between mobile and desktop users.

The project also evaluates each continent’s contribution to total revenue alongside account registrations, verified accounts, and session activity, providing a clear overview of regional business performance and user engagement.

**Key Metrics:** Total Revenue, Revenue Share, Mobile Revenue, Desktop Revenue, Accounts, Verified Accounts, Sessions

**Tools:** SQL, Google BigQuery



## 📧 [Monthly Email Activity by Account](https://github.com/jhgjvvjk/-Email-Activity-Distribution-Analysis/tree/main)

Analyzed monthly email communication activity across customer accounts using SQL and Google BigQuery. The analysis measures how many messages were sent to each account and calculates each account’s share of the total email volume within a given month.

The project also identifies the first and last email dates for every account during each month, making it possible to examine the distribution and timing of email activity across the customer base.

**Key Metrics:** Messages Sent per Account, Share of Monthly Email Volume, First Sent Date, Last Sent Date

**Tools:** SQL, Google BigQuery



## 🗄️ [Bookcases Revenue Analysis by Continent](https://github.com/jhgjvvjk/Bookcases-Revenue-Analysis-by-Continent/tree/main)

Analyzed product revenue across different continents using SQL and Google BigQuery, with a specific focus on the Bookcases & Shelving Units category.

The analysis calculates total revenue for each continent and isolates the revenue generated by bookcases and shelving products. It also measures the category's percentage contribution to total regional revenue, making it possible to compare its sales importance across different geographic markets.

**Key Metrics:** Total Revenue, Bookcases Revenue, Bookcases Share of Total Revenue

**Tools:** SQL, Google BigQuery

---

# Google Sheets

## 📊 [Global Sales Performance & Business Analysis](https://docs.google.com/document/d/1fvqfDKG5aV7YqnnMeXuFnTzzCB3PJjgmDxp_YW2_WPA/edit)

A comprehensive business and sales analysis covering 1,330 orders across 45 countries, with over $1.7B in revenue and $501M in profit. The project explores overall business performance, product profitability, geographic distribution, sales channels, logistics, and sales dynamics across multiple years.

The analysis includes ABC/Pareto segmentation of product categories by revenue, profit, and units sold; regional and country-level profitability analysis; comparison of online and offline sales channels; delivery-time analysis; and investigation of monthly, yearly, and weekly sales patterns.

Time-series analysis was used to identify trends, seasonality, and recurring demand patterns, while geographic and category-level analysis helped identify the company's strongest markets and most valuable product segments. A summary dashboard was created to consolidate the main KPIs and business insights.

**Key Metrics:** $1.70B Revenue | $501.4M Profit | 6.57M Units Sold | 1,330 Orders | 45 Countries

**Key Analysis:** ABC Analysis • Profitability • Geographic Analysis • Sales Channels • Logistics • Trends & Seasonality • KPI Dashboard
Google Sheet: https://docs.google.com/spreadsheets/d/19P-Faf14zlvE3hKBz02-TPQndP5mIqAk2ajFWOhibcE/edit?gid=538153630#gid=538153630

**Tools:** Google Sheets • Pivot Tables • Data Visualization • Business Analysis



## 🌐 [Website Traffic & Page Performance Analysis](https://docs.google.com/spreadsheets/d/1FNT4C56vE_XG-0kp_iKy9PTKt86Y4rG7AvvHr3zeGBY/edit?gid=824809908#gid=824809908)

Analyzed website traffic and page-level performance data using Google Sheets. The dataset contains more than 28,000 records with metrics related to visitor activity and user engagement across different website pages.

The analysis included pageviews, unique pageviews, entrances, average time on page, bounce rate, and exit rate. I also calculated relative page performance metrics and used summary statistics such as average, median, minimum, and maximum values to better understand the distribution of website activity.

The project demonstrates how spreadsheet-based analysis can be used to explore website performance, compare individual pages, and summarize large web analytics datasets.

**Key Metrics:** Pageviews, Unique Pageviews, Average Time on Page, Entrances, Bounce Rate, Exit Rate

**Tools:** Google Sheets



## 🛍️ [E-commerce Product & Customer Review Analysis](https://docs.google.com/spreadsheets/d/128ncjE-em70LlJySHSFzpUmoknEp53vR0kBMfM8Jq4Q/edit?gid=424287296#gid=424287296)

Analyzed e-commerce product data using Google Sheets to explore pricing, product categories, customer reviews, and differences between customer segments.

The analysis uses pivot tables to compare average review activity across men's, women's, and kids' products within Shoes, Clothing, and Accessories. It also examines product pricing across categories and colors and compares selling prices with customer review activity.

The analysis identified differences in review engagement between product segments and showed that the higher-priced Shoes category also had substantially higher average review activity than Clothing and Accessories.

**Key Metrics:** Selling Price, Average Reviews, Product Category, Customer Segment, Product Color, Average Rating

**Tools:** Google Sheets



## 👟 [Adidas Product Performance & Rating Analysis](https://docs.google.com/spreadsheets/d/1Rv-2RH6W0D2Fg1p86uHIsnM6Q0mqleHxPkPrPMbhIRc/edit?gid=170468689#gid=170468689)

Analyzed Adidas product data using Google Sheets to explore pricing, customer ratings, review activity, and differences across product categories and customer segments.

The analysis uses pivot tables to compare product performance across Shoes, Clothing, and Accessories, including women's, men's, and kids' segments. Customer ratings were also analyzed across different product colors and segments to identify variations in product feedback.

Visualizations were created to examine the distribution of selling prices and compare review activity between product categories. The price distribution showed a clear right-skewed pattern, with most products concentrated in lower price ranges and a small number of high-priced outliers.

**Key Metrics:** Selling Price, Average Rating, Review Count, Median Reviews, Product Category, Customer Segment

**Tools:** Google Sheets

---

# Tableau Dashboards

## [Website Session & Traffic Analysis ](https://public.tableau.com/app/profile/vladyslav.hordiienko7457/viz/SessionAnalysis_17762494154450/SessionAnalysis?publish=yes)

This Tableau dashboard gives a detailed analysis of website sessions and traffic distribution across multiple dimensions. It explores user activity by browser, traffic channel, country, device type, operating system, and browser language, providing an overview of how users access and interact with the website.

The dashboard also tracks session dynamics over time, making it possible to identify changes and peaks in overall website activity. Traffic channel and continent trends are presented both by total session volume and as a percentage of overall traffic, allowing their contribution and changes over time to be compared.

Geographic and technology-based visualizations provide additional insight into the distribution of users across countries, devices, operating systems, and browsers. Interactive dashboard elements allow different segments of website traffic to be explored and compared within a single analytical view.

Tools: Tableau

Key Areas: Session Analysis, Traffic Analysis, User Segmentation, Geographic Analysis, Trend Analysis, Data Visualization



## [Email Metrics & Performance Dashboard](https://public.tableau.com/app/profile/vladyslav.hordiienko7457/viz/EmailsAnalysis/EmailAnalysis)

This project provides a comprehensive view of email performance and user engagement, focusing on key metrics such as Open Rate, Click Rate, and Click-to-Open Rate (CTOR). These metrics are used to evaluate how users interact with email communications and identify differences in engagement levels.

The analysis explores changes in email activity over time, highlighting trends and fluctuations across the observed period. Results are also compared across countries based on email volume and engagement metrics, allowing geographic differences in user behavior and communication performance to be identified.

An interactive Tableau dashboard brings the main KPIs, historical trends, and country-level comparisons together in a single analytical view, making it easier to explore overall performance and individual market results.

Tools: Tableau

Key Areas: Email Analytics, Engagement Metrics, KPI Tracking, Trend Analysis, Geographic Comparison
