# Airline-Analysis-
This project will present key metrics related to flight delays.
### Project Overview
In Los Angeles International Airport there is a routine investigation to determine unpunctual flights. A report is created with the data that is derived from the routine investigation.
This report will highlight various aspects of flight punctuality. The goal of the report is to show an up-to-date overview of the situation and identify flight accumulations. Based on the report internal processes can be adjusted accordingly.
### Data Source
Airline_ data: The dataset used here is from 2015 to 2017.
The primary dataset used for this analysis is from an SQL server
### Code
```sql
Select * FROM Flights 
WHERE fl_date BETWEEN '2015-01-01' and '2017-12-31'
AND  (origin  = 'LAX' or dest = 'LAX')
AND cancelled = 'FALSE' 
AND diverted = 'FALSE';
```

### Tools
Mysql--Power BI
### Data Preparation

   1. Data loading and inspection.
   2. Handling Missing values.
   3. Resolve data quality issues.
   4. Data Cleaning and Formating.
   
### EDA (Exploratory Data Analysis)

   1. Which key figures are important for flights and delays?
   2. Which three airlines are the most delayed per flight?
   3. What is the percentage of delayed flights for these airlines?
   4. During which periods are flight delays particularly bad?

 
