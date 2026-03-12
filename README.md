# COVID-19 Data Analysis Project  

## Project Overview   
The project gives us an idea on the impact of Corona Virus globally in terms of confirmed cases, deaths reported, number of recoveries and active cases in India. It also shows how India was affected since the pandemic started.
The project highlight the impact of the virus on states/territories in India, it influence and the vaccination status of total sample size. 

The main goal is to clean, process and visualize, the datasets for further use in analytics and research.

## Objective  
The purpose of this Python project is to analyse and visualize COVID-19 statistics across different states/territories in India. The project aims to provide clear data-driven insights into the pandemic’s impact by focusing on:
- Identified states most affected by COVID-19 in terms of confirmed cases.  
- Highlighted states with the lowest vaccination coverage.  
- Compared vaccination rates between male and female populations.  
- Ranked states with the highest death tolls.  
- Tracked states with the largest number of active cases.

## Key Steps & Processes

### 1. Data Import & Exploration  
- Imported the dataset using **Pandas** from an Excel CSV file.  
- Conducted initial data exploration: checked columns, data types, and null values.  
- Identified redundant and inconsistent data for cleaning.

 ###  2. Data Cleaning  
- Removed unnecessary columns such as **Time**, **ConfirmedIndianNational**, **ConfirmedForeignNational** and **Sno** columns.  
- Handled missing data and standardized all column names for smooth analysis.
-   Converted **date** column to **datetime** format
-   Converted numeric columns; **Confirmed**, **Cured** and **Deaths** to the accurate data types.
-   Created **Active Cases** column which was calculated by: Total number of **Confirmed**  cases – sum of **Cured**  cases + **Death** reported =  **Active Cases**.
- Renamed **Updated On** (column) to **Vaccine Date**.
- Removed rows where **State** was wrongly named **India**. 
- Renamed **Total Individuals Vaccinated** column to **Total**.

 ### Data Source
 The primary dataset used for this analysis is the **covid_vaccine_statewise.csv** and **covid_19_india.csv** file, containing detailed information about Covid 19 pandemic in India.
 The Dataset was downloaded from **Kaggle**.

 ### Tools/Software used
 - MS Office Pro Plus/Excel 2013 - Dataset (**covid_vaccine_statewise.csv** and **covid_19_india.csv**)
 - Python
 - Python Libraries: Pandas, Numpy, Matplotlib and Plotly
 - Anaconda Navigator and Jupyter Notebook

### Data Analysis
Our analysis was executed using Python Programming Language with Jupyter Notebook.
  
### Screanshots of Analysis

<img width="800" height="500" alt="five_most_affected_states" src="https://github.com/user-attachments/assets/7636119c-e915-4d79-8828-5fe49daa31d7" />
<img width="800" height="500" alt="top_10_state_deaths" src="https://github.com/user-attachments/assets/abb629bc-a6f5-466f-87b3-795c2245dc01" />
<img width="1152" height="185" alt="top_10_state_deaths_histogram" src="https://github.com/user-attachments/assets/bb02d371-8f88-41f0-b8bd-baba99323ca1" />

<img width="800" height="500" alt="top_5_vaccinated_states_histograph" src="https://github.com/user-attachments/assets/bd0a5e3e-d976-4dca-b31b-bfffbdbe05e7" />
<img width="848" height="522" alt="most_vaccinated_states" src="https://github.com/user-attachments/assets/db0ed1b7-56e2-4de7-aad0-283013f499a9" />
<img width="929" height="464" alt="top_5_vaccinated_states_histograph" src="https://github.com/user-attachments/assets/69068601-c029-4e24-91aa-659f24d88d2e" />
<img width="947" height="154" alt="top_5_vaccinated_states_code" src="https://github.com/user-attachments/assets/914cba41-26b9-4498-9fa2-429d7ecda707" />



