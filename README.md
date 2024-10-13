# LITA_class_Documentation
### Project Title
## A comparative study of International Breweries Sales Operations

### Table of Contents
[Project Overview](#project-overview)

[Tools Used](#tools-used)

[Data Cleaning and Preparation](#data-cleaning-and-preparation)

[Data Analysis](#data-analysis)

[Data Visualization](#data-visualization)

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
```
Sales Data was imported into Excel from SQL server database
## chart 1
This chart shows the revenue of each countries from 2017_2019
![Screenshot 2024-10-13 223555](https://github.com/user-attachments/assets/5391cf65-d697-404b-a906-ecd3a51d42ba)

## chart 2
This chart shows the revenue of various countries from each products (Brand)
![Screenshot 2024-10-13 223620](https://github.com/user-attachments/assets/dee38d6f-6f6a-4073-a2df-8537078df957)
```
### Results
## Chart 1
In 2017, Nigeria generated the highest revenue
In 2018, Nigeria maintained it's top position
In 2019, Ghana surpassed Nigeria, recording the highest revenue

## chart 2


