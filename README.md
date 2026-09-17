🛍️ Nykaa Product Analysis — Web Scraping & Data Analytics
📌 Project Overview

This project focuses on collecting, cleaning, analyzing, and visualizing product data from Nykaa using Python-based web scraping and data analytics techniques.

The analysis covers three product categories:

🩺 Healthcare
💄 Beauty – Skincare Sample
👶 Baby

The project follows an end-to-end data analytics workflow:

Web Scraping → Data Cleaning → Exploratory Data Analysis → Visualization → Business Insights → Power BI Dashboard

🎯 Project Objectives
Collect product information from Nykaa using web scraping.
Analyze Healthcare products.
Analyze Beauty/Skincare products.
Analyze Baby products.
Clean and preprocess the scraped data.
Analyze product prices, discounts, ratings, and reviews.
Identify highly reviewed and highly rated products.
Compare performance across product categories.
Build an interactive Power BI dashboard.
Generate meaningful business insights and recommendations.
🛠️ Technologies Used
Technology	Purpose
🐍 Python	Web scraping and data processing
Selenium	Extracting dynamic website data
BeautifulSoup	HTML parsing
Pandas	Data cleaning and analysis
NumPy	Numerical operations
Jupyter Notebook	Development and analysis
Excel	Data storage and documentation
Power BI	Dashboard and visualization
🌐 Web Scraping

Selenium was used to automate the Chrome browser and collect product information from Nykaa.

Product attributes collected
Product Name
Brand
MRP
Selling Price
Discount Percentage
Rating
Rating Count
Review Count
Pack Size
Stock Status
Product URL
Scraped Date
📊 Dataset

The final master dataset contains:

Category	Products
Healthcare	31
Beauty	31
Baby	20
Total	82

The Beauty category represents a Skincare sample collected for the project.

🧹 Data Cleaning & Preprocessing

The scraped data was cleaned using Pandas.

Cleaning steps
Removed duplicate product URLs.
Identified duplicate Product Name + Brand combinations.
Converted MRP and Selling Price into numeric values.
Converted Rating, Rating Count, and Review Count into numeric values.
Calculated Discount Percentage.
Handled records with missing essential product information.
Created Price Range categories.
Prepared a final master dataset for analysis.
🔎 Exploratory Data Analysis

The following analyses were performed:

Product distribution by category
Average selling price by category
Average discount by category
Average rating by category
Total reviews by category
Top brands by product count
Top products by review count
Highest discounted products
Price range distribution
Selling Price vs Review Count
📈 Key Findings
Category-wise analysis
Category	Avg. Selling Price	Avg. Discount	Avg. Rating
Healthcare	₹1,460.74	17.90%	4.29
Beauty	₹955.29	12.10%	4.37
Baby	₹630.75	8.85%	4.28
Important observations
Healthcare has the highest average selling price in the scraped sample.
Healthcare also has the highest average discount.
Beauty has the highest average rating.
Beauty has the highest total review count in the scraped sample.
Baby products have the lowest average selling price.
📊 Power BI Dashboard

An interactive Power BI dashboard was created to present the analysis.

Dashboard includes
Total Products KPI
Average Selling Price
Average Discount
Average Rating
Number of Products by Category
Average Selling Price by Category
Average Discount by Category
Average Rating by Category
Top 10 Products by Review Count
Product Distribution by Price Range
Selling Price vs Review Count
Category Filter
Price Range Filter
💡 Business Recommendations
Use category-wise pricing analysis to support product positioning.
Evaluate promotional strategies for higher-priced Healthcare products.
Highlight highly rated and highly reviewed Beauty products.
Consider affordable bundles and introductory offers for Baby products.
Monitor customer ratings and reviews regularly.
Repeat the analysis periodically to track pricing and customer engagement trends.
📁 Project Structure
Nykaa_Product_Analysis/
│
├── 01_Data/
│   ├── healthcare_products_cleaned.csv
│   ├── healthcare_products_cleaned.xlsx
│   ├── beauty_products_cleaned.csv
│   ├── beauty_products_cleaned.xlsx
│   ├── baby_products_cleaned.csv
│   ├── baby_products_cleaned.xlsx
│   ├── nykaa_master_cleaned.csv
│   ├── nykaa_master_cleaned.xlsx
│   └── Nykaa_Final_Project_Data.xlsx
│
├── 02_Jupyter_Notebook/
│   └── Nykaa_Product_Analysis.ipynb
│
├── 03_PowerBI/
│   └── Nykaa_Product_Analysis_Dashboard.pbix
│
└── 04_Documentation/
    ├── nykaa_data_dictionary.csv
    ├── nykaa_data_cleaning_documentation.csv
    └── nykaa_project_documentation.xlsx
🔄 Project Workflow
Nykaa Website
      ↓
Web Scraping using Selenium
      ↓
Raw Product Data
      ↓
Data Cleaning using Pandas
      ↓
Master Dataset
      ↓
Exploratory Data Analysis
      ↓
Business Insights
      ↓
Power BI Dashboard
📌 Conclusion

This project demonstrates an end-to-end Web Scraping and Data Analytics workflow, starting from collecting real-world website data and ending with an interactive Power BI dashboard.

The project helped analyze product pricing, discounts, ratings, reviews, and category-level patterns and convert the collected web data into meaningful business insights.
