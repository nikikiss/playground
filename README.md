# playground

## Python
Some code snippets I wrote.

## Pandas
### [Woman vs Man Wage Comparison](./Pandas/Pandas-Woman_vs_Man_wage_gap.ipynb)
An analysis which introduces the gap between female and male hourly wages in London and in the UK, from 1997 to 2018. There are three different hourly rates for each gender, for each year and these are part-time, full-time and all (part-time and full-time weighted average) hourly rates. The source of data is London datastore. 

The analysis also includes an additional data frame with London living wage, UK living wage and national minimum wage (hourly rates).  

What is included in the analysis?:
- data import
- general data frame information
- data cleansing / replacement
- data visualization
- data filtering


## Excel

### [London district dashboard](./Excel/London_district_dashboard.xlsx)
An interactive dashboard which was built on the population projection dataset, downloaded from London datastore. The goal of the dash is to give a quick overview about the population for the chosen district (within London), for the chosen time period. The dash automatically refresh if the following parameters are changed from the drop down:
- district
- from year
- to year

The dash includes five sections:
- Absolute number of population for the two chosen years and average annual change (%)
- Distribution of the population, based on age groups for the chosen years
- Projection of population of the district from 2011 to 2050
- Gender distribution changes for the two chosen years
- Top districts based on the number of population for the analysis start and end year (including the district, even if it is out of top 10)
