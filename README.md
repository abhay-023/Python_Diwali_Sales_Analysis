📊 Sales & Customer Insights Dashboard

📌 Overview
This project presents an interactive Excel dashboard designed to analyze customer purchase behavior, product performance, and sales trends. The dashboard provides actionable insights into customer demographics, spending patterns, and regional sales distribution, helping businesses make data-driven decisions.

📂 Dataset Description
The dataset contains customer transaction records, including demographic and purchase details.
Column Name	Description
User_ID	Unique identifier for each customer
Cust_name	Name of the customer
Product_ID	Unique identifier for each product
Gender	Customer gender (Male/Female)
Age Group	Age range category (e.g., 0–17, 26–35)
Age	Exact age of the customer
Marital_Status	0 = Unmarried, 1 = Married
State	Customer’s state
Zone	Zone classification (Western, Southern, etc.)
Occupation	Customer’s occupation
Product_Category	Category of purchased product
Orders	Number of orders placed
Amount	Purchase amount
Status / unnamed1	Extra columns (removed during cleaning)

🛠 Data Cleaning & Transformation
Steps performed before dashboard creation:
✅ Removed duplicate records
✅ Handled missing values
✅ Dropped irrelevant columns (Status, unnamed1)
✅ Standardized categorical values (e.g., state names, zones)
✅ Converted numerical columns (Age, Amount, Orders) into proper formats

📊 Dashboard Features
The dashboard highlights the following insights:
Sales by Gender & Age Group → Understanding customer demographics
Top States & Zones by Revenue → Identifying strong-performing regions
Occupation-based Sales Analysis → Segmenting customers by profession
Product Category Insights → Finding the most purchased categories
Order & Revenue Trends → Tracking customer purchasing behavior
Marital Status Impact → Sales comparison between married/unmarried customers

🚀 How to Use
Open the Excel file containing the dashboard
Use slicers/filters to view insights by gender, age group, occupation, or region
Hover over charts to view detailed values
Combine filters for deeper insights (e.g., married women in 26–35 age group from Western zone)

🔑 Key Insights (Sample)
Majority of purchases are made by customers aged 26–35 years
Western Zone contributes the highest revenue
Married customers spend slightly more compared to unmarried customers
Automobile and Electronics are top-performing product categories

🛠 Tools & Technologies
Microsoft Excel – Dashboard creation
Power Query – Data cleaning & transformation
Pivot Tables & Charts – Data summarization
Slicers – Interactive filtering

📌 Future Enhancements
Automating data refresh from live sales system
Adding forecasting using Power BI / Excel predictive models
Creating role-based dashboards for Sales, Marketing, and Operations teams
