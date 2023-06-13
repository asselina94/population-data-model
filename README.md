<h3> population-data-model </h3>

<h1> Population Data Analysis with Interactive Visuals </h1>

<img width="1083" alt="Screenshot 2023-06-08 at 11 25 31" src="https://github.com/asselina94/population-data-model/assets/54496175/7f229052-6d02-4128-90bd-81ab02766445">

<strong>This repository contains a Power BI project that provides interactive visualizations and data analysis for Population data of different periods(2010-2040). </strong>
>
> <strong>The project is designed to help users gain insights, make data-driven decisions, and effectively communicate information through intuitive visualizations.</strong>

# Features
<em><strong>Interactive Dashboards</strong></em>: 
> The project includes interactive dashboards that showcase key metrics, trends, and performance indicators related to population and countries.<br>
> 
<em><strong>Data Sources</strong></em>: 
> The project utilizes data from Excel and Csv files.<br>
> 
<em><strong>Visualizations</strong></em>: 
> The visualizations in the project encompass a variety of charts, graphs, and tables to present data in a clear and meaningful way.<br>
> 
<em><strong>Filters and Slicers</strong></em>: 
> Users can filter and slice data to focus on specific time periods, regions, or other relevant dimensions to explore data in-depth.

# Steps
<ol>
 <li><em> Data cleansing:</em> clean data( removed duplicates and unrequired data, combined given multiple data sources) in Power Query Editor.</li>
 <li> <em> Data Transmorfation </em> - Multidimensional Star schema data model which includes (Fact population, DIM-region, DIM-age, DIM-gender).</li>
 
>> DIM - dimensial table. The idea is seperate or categorize the information because the more data you have the more complex the data model gets, while the more structured data should be organized. 
  
  ![Star](https://github.com/asselina94/population-data-model/assets/54496175/2707c20e-23e1-4983-b732-ae66a38f1a54)
  
 <li> <em>The Data model - Analyze Data, relationships.</em><br>
  In this project One to Many relationship was used and applied filters by gender. </li>
 <li> <em>Created Visuals in Report View.</em>
 Used Report level filters and Concept of Hierarchies and Slicers to combine multiple levels in one single visual.</li> <br>
</ol>
  
<img width="975" alt="Screenshot 2023-06-08 at 11 07 52" src="https://github.com/asselina94/population-data-model/assets/54496175/9d20ebaa-52ff-40e3-9b3f-7001eda1eb4e">

  
# Challenges
Challenging part was Data Model which included making correct relationships to connect Star scheme parts and DAX ( data analysis espressions).
> <strong>Solution:<strong>

