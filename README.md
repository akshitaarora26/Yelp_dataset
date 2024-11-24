# Yelp Dataset Analysis and Business Opportunity Exploration

Project Overview
This project analyzes the Yelp Dataset to explore a business opportunity for opening a new Acai Bowl restaurant in St. Louis. Using SQL and Python, we extracted, processed, and analyzed data from multiple JSON files in the Yelp Academic Dataset to derive insights about customer reviews, business locations, and market trends.

The goal is to identify the optimal location for a new Acai Bowl restaurant and assess its potential success based on customer feedback, business density, and category analysis.

## Dataset
The Yelp dataset includes the following JSON files:

1. yelp_academic_dataset_review.json: Contains reviews and ratings data.
2. yelp_academic_dataset_business.json: Contains business details, such as categories, location, and opening hours.
3. yelp_academic_dataset_checkin.json: Contains business check-in data.
4. yelp_academic_dataset_tip.json: Contains user tips and feedback.
5. yelp_academic_dataset_user.json: Contains user profile details.

All data files were processed and loaded into Azure SQL Server for analysis.

## Tools and Technologies
Programming Language: Python
Libraries: Pandas, SQLAlchemy, pyODBC, JSON
Database: Azure SQL Server
Environment: Kaggle Notebook
SQL Queries: Used for in-depth data analysis.

## Process Workflow
1. Data Extraction:

- Loaded JSON files using json and pandas libraries.
- Converted data into structured dataframes.
2. Data Preprocessing:

- Dropped duplicates and null values.
- Converted date columns to appropriate datetime formats.
3. Database Setup:
- Established a connection to Azure SQL Server using SQLAlchemy and pyODBC.
- Uploaded dataframes to SQL Server as relational tables.
4. Analysis Queries:
- Analyzed Acai Bowl categories and their distribution across cities.
- Identified market trends in St. Louis for Acai Bowls.
- Explored customer feedback, average ratings, tips, and business hours.
- Assessed busiest postal codes in St. Louis for optimal business location.

## Key Findings
1. Category Analysis:
- Acai Bowl restaurants are sparse in the dataset, presenting an opportunity.
- Most Acai Bowl restaurants in the U.S. are concentrated in Tampa, while St. Louis has only one.
2. Customer Feedback:
- Reviews for the existing Acai Bowl restaurant in St. Louis indicate dissatisfaction with taste, suggesting room for competition.
3. Market Potential:
- Many reviews in St. Louis mention breakfast and morning preferences, hinting at demand for early-morning offerings.
4. Optimal Location:
- The busiest postal codes in St. Louis are 63108 and 63110.
- Since the existing Acai Bowl restaurant is in 63108, 63110 offers a strategic opportunity to attract new customers.


## Conclusion
Based on the analysis, opening a new _Acai Bowl restaurant in St. Louis_ , postal code 63110 could fill a market gap and cater to unmet demand for healthy breakfast options.

## How to Run This Project
Prerequisites
- Python 3.7 or higher
- Kaggle environment or local Jupyter Notebook
- Azure SQL Server account
