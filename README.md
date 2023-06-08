# population-data-model

<img width="1083" alt="Screenshot 2023-06-08 at 11 25 31" src="https://github.com/asselina94/population-data-model/assets/54496175/7f229052-6d02-4128-90bd-81ab02766445">

This repository contains a Power BI project that provides interactive visualizations and data analysis for Population data of different periods(2010-2040). The project is designed to help users gain insights, make data-driven decisions, and effectively communicate information through intuitive visualizations.

# Features
Interactive Dashboards: The project includes interactive dashboards that showcase key metrics, trends, and performance indicators related to population and countries.
Data Sources: The project utilizes data from Excel and Csv files.
Visualizations: The visualizations in the project encompass a variety of charts, graphs, and tables to present data in a clear and meaningful way.
Filters and Slicers: Users can filter and slice data to focus on specific time periods, regions, or other relevant dimensions to explore data in-depth.

# Steps
1 Data cleansing: clean data( removed duplicates and unrequired data, combined given multiple data sources) in Power Query Editor.
2 Data Transmorfation - Multidimensional Star schema data model which includes (Fact population, DIM-region, DIM-age, DIM-gender).
  DIM - dimensial table. The idea is seperate or categorize the information because the more data you have the more complex the data model     gets, while the more structured data should be organized. 
  
  ![Star](https://github.com/asselina94/population-data-model/assets/54496175/2707c20e-23e1-4983-b732-ae66a38f1a54)
  
3 The Data model - Analyze Data, relationships. 
  In this project One to Many relationship was used and applied filters by gender. 
4 Created Visuals in Report View

  
# Challenges
Challenging part is Data model which include relationships and DAX ( data analysis espressions)
