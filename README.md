# customer_behaviour_analysis
Data Analytics Project showcasing Customer Behaviour Analysis using Python, SQL and Power BI

Overview:
This project focuses on analyzing customer shopping behavior using transactional retail data. The objective was to identify customer purchasing patterns, product preferences, revenue trends, and subscription behavior through data analysis and visualization.

The project involved:

Data cleaning and preprocessing in Python
Exploratory Data Analysis (EDA)
SQL-based business analysis using PostgreSQL/MySQL/SQL Server
Interactive dashboard creation in Power BI
Business reporting and presentation preparation using Gamma

Dataset:
The dataset contains customer shopping transaction records with information related to:

Customer demographics
Product categories
Purchase amounts
Subscription status
Discounts and promo codes
Shipping preferences
Product reviews

Dataset Details:
Rows: 3,900
Columns: 18

Key Features:
Age
Gender
Location
Category
Item Purchased
Purchase Amount
Subscription Status
Review Rating
Shipping Type
Frequency of Purchases

Tools & Technologies Used:

Programming & Analysis:
Python
Pandas

Database:
PostgreSQL

Visualization & Reporting:
Power BI
Gamma (for PPT creation)

Project Workflow:

1. Data Loading
Imported dataset using Pandas
Explored structure using:
df.info()
df.describe()

2. Data Cleaning
Handled missing values
Standardized column names into snake_case
Removed redundant columns
Performed consistency checks

3. Feature Engineering
Created additional features such as:

age_group
purchase_frequency_days

4. Exploratory Data Analysis (EDA)
Performed analysis to understand:

Customer demographics
Purchase behavior
Revenue distribution
Product popularity
Subscription trends

5. SQL Analysis
Executed business-focused SQL queries including:

Revenue by gender
Top-rated products
Shipping type comparison
Customer segmentation
Subscription analysis
Revenue by age group

6. Dashboard Development
Built an interactive Power BI dashboard to visualize:
Revenue trends
Customer segments
Product performance
Subscription insights
Sales by category and age group

7. Reporting & Presentation
Created a detailed project report
Designed presentation slides using Gamma

Dashboard Highlights:

The Power BI dashboard includes:
KPI cards
Revenue analysis
Customer segmentation
Category-wise sales
Subscription analysis
Age-group insights
Interactive filters and slicers

Key Results & Insights:
Male customers generated higher total revenue
Certain products consistently received better ratings
Loyal customers formed the majority customer segment
Express shipping users showed higher average spending
Subscription users contributed significantly to overall revenue

Business Recommendations
Improve customer loyalty programs
Promote subscription benefits
Optimize discount strategies
Focus marketing on high-revenue customer groups
Highlight top-performing products in campaigns

How to Run the Project
1. Clone the Repository
git clone <repository-link>
cd customer-shopping-analysis

2. Install Required Libraries
pip install pandas numpy matplotlib seaborn sqlalchemy

3. Run Python Analysis
python analysis.py

4. Connect Database
Import cleaned data into PostgreSQL/MySQL/SQL Server
Execute SQL queries for business analysis

6. Open Power BI Dashboard
Open .pbix file in Power BI Desktop

Project Deliverables
Python EDA Notebook
SQL Query Scripts
Power BI Dashboard
Project Report
Presentation Slides
