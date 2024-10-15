# LITA_class_Documentation
### Project Title
## A comparative study of International Breweries Sales Operations

### Table of Contents
[Project Overview](#project-overview)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

[Results and Recommendations](#results-and-recommendations)

### Project Overview
This project aims to analyze and visuaize revenue trends across countries and products of International Breweries to fuel growth and expansion
## Objectives
- To analyze revenue streams across countries and products to inform business strategies and drive growth
- To identify top performing products and countries

### Tools Used
```
- SQL
  1. For Data Cleaning
  2. For Data Analysis
- Microsoft Excel
  1. For Data Visualization
```

### Data Cleaning and Preparation
```
   In the inital phase of the Data cleaning and preparations, we performed the following;
     1. Data Loading and Inspection
     2. Handling missing variables
     3. Data claning and formatting
```

### Data Analysis
```
```SQL
select sum(profit) as TotalProfit from [dbo].[InternationalBreweries LITA]

select Brands, sum(profit) as TotalProfit 
from [dbo].[InternationalBreweries LITA]
where countries = 'Nigeria' and years = '2017'
Group by Brands
order by 2 desc
```

### Data Visualization

Sales Data was imported into Excel from SQL server database
## Chart 1
This chart shows the revenue of each countries from 2017_2019
![Screenshot 2024-10-13 223555](https://github.com/user-attachments/assets/5391cf65-d697-404b-a906-ecd3a51d42ba)

## Chart 2
This chart shows the total revenue from products of International breweries (Brands)
![Screenshot 2024-10-13 223620](https://github.com/user-attachments/assets/dee38d6f-6f6a-4073-a2df-8537078df957)

### Results and Recommendations
```
## Chart 1
-In 2017, Nigeria generated the highest revenue
 This shows that Nigeria has a strong market presence
-In 2018, Nigeria maintained it's top position
-In 2019, Ghana surpassed Nigeria, recording the highest revenue
 This shows that there are emerging opportunities in Ghana
 Therefore, it is recommended that marketing strategies should be developed to tap into ghana's growth potential

## Chart 2
-Castle lite generated the highest revenue in Benin, Ghana, Nigeria, Senegal and Togo
-Budweiser ranked second in revenue across the countries
Castle lite's dominance across the countries indicates strong brand recognition and customer preference 
 Therefore, it is recommended that International Breweries keep investing in castle lite's marketing and distribution
```






