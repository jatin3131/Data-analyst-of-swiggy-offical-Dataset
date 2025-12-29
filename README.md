Swiggy Food Delivery Data Analytics
Project Overview

This project focuses on analyzing real-world food delivery market data representing restaurant listings from the Swiggy platform. The objective is to uncover meaningful insights related to customer ratings, cuisine popularity, promotional offers, pricing patterns, and food delivery performance across different locations.

The analysis combines Python-based exploratory data analysis (EDA) with interactive dashboards built using Power BI, providing both technical depth and business-focused insights.


IMPORTANT:- FOR PREPROCESSING IN PYTHON CODE, REFER PDF FILE IN THIS REPSITORY.
(AS Github DON'T SUPPORT JUPYTER(IPYNB) FILE)

---------------------------------------------------------------
 -----Objectives

Identify food categories with the highest customer ratings

Analyze which cuisines receive the most promotional offers

Evaluate delivery time variations across different locations

Determine which food types experience longer delivery times due to preparation or availability constraints

Present insights through interactive and business-friendly visualizations

---- Dataset Information

Source: Public Swiggy restaurant dataset available on Kaggle

Description: Dataset represents real Swiggy restaurant listings and customer-facing information

-Key Features:

Restaurant Name

City / Location

Food Type (Cuisines)

Price

Average Rating

Total Ratings

Offers / Discounts

Delivery Time

 Note: This dataset is publicly available for analytical and educational purposes and reflects real restaurant data listed on the Swiggy platform.

------Tools & Technologies

Python

Pandas, NumPy — Data preprocessing & analysis

Matplotlib, Seaborn — Data visualization

Power BI — Interactive dashboards

Jupyter Notebook — Development environment

------Data Preprocessing & Feature Engineering

Handled missing and inconsistent values

Removed duplicate restaurant records

Standardized text data for cities and food types

Converted price, ratings, and delivery time into numeric formats

Extracted primary cuisine from multi-cuisine listings

Created cuisine-level and city-level aggregated features

------Exploratory Data Analysis

The following analyses were performed:

City-wise distribution of restaurants

Cuisine popularity analysis

Price distribution and city-level pricing trends

Rating distribution across food categories

Relationship between price, ratings, and offers

Delivery time comparison by location and cuisine

-----Visualizations include:

Bar charts

Histograms

Scatter plots

Correlation heatmaps

Power BI Dashboards

------Interactive dashboards were created in Power BI to visualize:

Top-rated food categories

Cuisines receiving maximum offers

Locations with higher delivery times

Cuisine-wise delivery performance

These dashboards help translate technical findings into actionable business insights.

======= Key Insights

Certain food categories consistently receive higher customer ratings

Promotional offers are more frequent for specific cuisines

Delivery time varies significantly across locations

Some cuisines take longer to deliver due to preparation complexity or availability issues

High-priced restaurants do not always guarantee higher ratings

====== Conclusion

This project demonstrates an end-to-end data analytics workflow, from raw data preprocessing to advanced visualization and insight generation. By combining Python-based analysis with Power BI dashboards, the project provides a realistic view of how food delivery platforms can leverage data to improve customer experience and operational efficiency.

===== Future Enhancements

Predict delivery time using machine learning models

Sentiment analysis on customer reviews

Time-based analysis (peak hours & demand patterns)

Integration of geospatial analysis

=====Author

Jatin
Aspiring Data Analyst | Python | Power BI | Data Analytics
