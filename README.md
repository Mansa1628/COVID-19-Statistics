# COVID-19 Data Exploration and Dashboard

## Project Overview
Amidst the global turmoil caused by the COVID-19 pandemic, the need for accessible, reliable data became paramount. The COVID-19 Data Exploration and Dashboard project was born out of this necessity, aiming to provide a comprehensive analysis and visualization platform for understanding the pandemic's impact. Leveraging datasets from sources like Our World in Data, the project utilized SQL data exploration techniques to extract insights and develop a Tableau dashboard. By offering stakeholders a user-friendly interface to explore key metrics such as confirmed cases, deaths, and vaccinations, the project aimed to empower informed decision-making and foster dialogue on public health strategies and socio-economic impacts.


## Project Scope
The project utilized COVID-19 data provided by Our World in Data, focusing on metrics such as confirmed cases, deaths, vaccinations, and various socio-economic indicators. The data exploration phase involved SQL queries to extract, clean, and transform the dataset for analysis. Subsequently, a Tableau dashboard was developed to visualize key insights and trends.

## Tools and Technologies
The project utilized the following tools and technologies:

- **SQL (Structured Query Language):** The primary language used for data manipulation, exploration, and analysis.
- **SQL Server Management Studio (SSMS):** For database creation, data parsing, and initial data exploration.
- **Tableau:** For creating a variety of visualizations and interactive dashboards based on SQL query findings.
- **Excel:** While not directly used in the project, the dataset obtained from 'Our World in Data' was in Excel format, serving as the initial file type for data exploration.

This combination of tools facilitated a comprehensive approach to the analysis, from database creation and exploration using SQL to visual representation and interactive dashboards in Tableau. The dataset's initial format in Excel underscored the importance of diverse tools in handling and extracting insights from real-world datasets.

## Data Exploration
The COVID-19 dataset from Our World in Data contains various metrics sourced from organizations such as WHO, Johns Hopkins University, and official government reports. The dataset includes information on confirmed cases, deaths, hospitalizations, ICU admissions, testing, vaccinations, and policy responses. The data exploration phase involved two main SQL scripts executed on SQL Server:

### table_creation.sql
This script focuses on creating tables and performing initial data processing steps to prepare the dataset for analysis. It includes the following tasks:

- Specifying the specific database name
- Creating tables such as `covid_deaths` and `covid_vaccinations` from the raw dataset
- Retrieving column data types and correcting them as necessary for easier data exploration

### data_exploration.sql
This script consists of steps taken after the initial table creation, focusing on extracting relevant data for exploratory data analysis. It includes the following tasks:

- Selecting relevant data for analysis, including metrics such as confirmed cases, deaths, and vaccinations
- Finding potential Key Performance Indicators (KPIs) such as total cases, total deaths, and total vaccines administered
- Conducting comparative analysis:
  - Comparing total cases vs. total deaths (%) in the United States
  - Sorting countries by the highest death count per population
  - Calculating metrics like mortality rate from contracting COVID-19 and comparing total population with total vaccinations using rolling counts and percentages

These SQL scripts were crucial in preparing and exploring the COVID-19 dataset, providing the necessary foundation for subsequent analysis and visualization.

## Tableau Dashboard

The Tableau dashboard was designed to visualize key insights and trends related to COVID-19, including total cases, deaths, vaccinations, and their distribution across countries and regions. The dashboard includes KPIs, text charts, symbol maps, and area graphs to provide a comprehensive overview of the pandemic's impact.

### Dashboard Components
#### Key Performance Indicators (KPIs)
- Total cases recorded
- Total deaths recorded
- Total vaccine doses administered

#### Text Chart
- Total cases and deaths by country/region

#### Symbol Map
- Population percentage impacted by COVID-19

#### Area Graphs
- COVID cases reported over time by region
- COVID-related deaths over time by region
- Vaccines administered over time by region

## Project Conclusion
The COVID-19 Data Exploration and Dashboard project has provided invaluable insights into the pandemic's impact through meticulous data analysis and visualization. By leveraging SQL queries and Tableau's visualization capabilities, the project distilled complex COVID-19 datasets into actionable insights accessible to a broad audience. The interactive Tableau dashboard serves as a centralized platform for tracking key metrics and empowering stakeholders to make informed decisions. Moving forward, these insights will continue to inform efforts to combat the pandemic and shape public health strategies, highlighting the project's lasting impact on data-driven decision-making in public health crises.

## Recommendations and Future Work
- Continuously update the dashboard with the latest COVID-19 data.
- Enhance interactivity and user experience by adding more filters and drill-down options.
- Conduct further analysis to identify correlations and causal relationships between variables.
