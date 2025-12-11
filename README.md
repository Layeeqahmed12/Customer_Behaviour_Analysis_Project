Customer Shopping Behavior Analysis

A complete end-to-end Data Analytics Project that covers the full workflow: loading data in Python, performing Exploratory Data Analysis, cleaning and preprocessing, running advanced SQL queries in MySQL/PostgreSQL/SQL Server, building an interactive Power BI dashboard, and creating a final report and presentation.

📌 Overview

This project analyzes customer shopping behavior to uncover trends in spending, product performance, subscription impact, discount usage, and customer segmentation.
It demonstrates practical skills in Python, SQL, and Power BI to solve real-world business questions and generate actionable insights.

📂 Dataset

Name: customer_shopping_behavior.csv

Size: ~3900 rows

Contains: customer demographics, purchase details, product category, shipping types, review ratings, and more.

🛠 Tools & Technologies

Python → Pandas, NumPy, Matplotlib, Seaborn

SQL → MySQL / PostgreSQL / SQL Server

Power BI → Dashboard creation

Jupyter Notebook → EDA & cleaning

Gamma App → PPT generation

GitHub → Project hosting and documentation

📘 Project Steps
1. Load the Dataset in Python

Imported and inspected raw data

Standardized column names

Checked for missing values and inconsistencies

2. Perform EDA

Distribution of customer age, spending, product popularity

Trends across gender, shipping type, subscription status

Correlation between key variables

3. Data Cleaning

Handling missing values

Removing duplicates

Converting data types

Feature engineering (Age Groups, Customer Segments)

4. Load Clean Data to SQL

Connected Python ↔ SQL using SQLAlchemy + PyMySQL

Exported cleaned DataFrame to SQL table (customer)

Verified transformed dataset using SQL queries

5. SQL Analysis

Included advanced SQL queries such as:

Revenue by gender

Products with highest average ratings

Impact of discounts

Customer segmentation (New, Returning, Loyal)

Top products within each category

Revenue by age groups

(SQL file included in repository)

6. Power BI Dashboard

Designed an interactive dashboard with:

Total revenue analytics

Customer segmentation insights

Product-wise performance

Discount and subscription behavior

Shipping type comparisons

(PBIX file included)

7. Final Report & Presentation

Report summarizing insights (PDF)

Business-ready presentation created using Gamma (PPT)

📊 Dashboard Preview

Add screenshot here
(Use this placeholder when uploading to GitHub)

📈 Key Results

Identified top revenue-generating age groups

Found that subscribers and repeat buyers contribute significantly higher revenue

Highlighted products with the strongest rating and demand

Discovered discount usage patterns

Built clear KPIs for decision-making

▶ How to Run This Project
1. Clone Repository
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git

2. Install Python Dependencies
pip install pandas numpy matplotlib seaborn sqlalchemy pymysql

3. Open Notebook
jupyter notebook

4. Configure SQL Connection

Update the credentials in notebook:

engine = create_engine("mysql+pymysql://root:password@localhost:3306/database_name")

5. Run SQL Scripts

Import Customer_Shopping_Behaviour_Analysis.sql into your SQL database.

6. Open Power BI File

Load customer_shopping_behavior_dashboard.pbix and refresh the data source.

📁 Repository Structure
├── customer_shopping_behavior.csv
├── Customer_Behaviour_Analysis.ipynb
├── customer_shopping_behavior_dashboard.pbix
├── Customer_Shopping_Behaviour_Analysis.sql
├── report.pdf
├── presentation.pptx
└── README.md

🤝 Contact

If you want to collaborate or discuss the project, feel free to connect!
