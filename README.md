# Census Data Analysis and Community Insights
Exploratory data analysis of mock census data using Python, Pandas, Matplotlib and Seaborn, with evidence-based recommendations for local development.

## Project Overview

This project analyses a mock census dataset using Python to understand population characteristics, identify data quality issues, and provide evidence-based recommendations for local development.

The analysis focuses on demographic characteristics, employment, marital status, religion, and other population attributes. The findings are used to evaluate potential community investment priorities, including educational facilities and transport infrastructure.

## Objectives

- Inspect and clean the census dataset.
- Identify and handle missing values.
- Perform exploratory data analysis (EDA).
- Analyse relationships between selected demographic variables.
- Communicate key findings through visualisations.
- Develop recommendations based on the available evidence.

## Tools and Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Data Cleaning

The project examines missing values in several columns and applies documented handling methods, including:

- Replacing missing surnames with `Unknown`.
- Filling missing relationship-to-household-head values using the mode, where appropriate.
- Representing marital status as `N/A` for children under 18 where the information is not applicable.
- Treating blank infirmity values as `No Infirmity`, based on an explicit analytical assumption.
- Filling missing religion values using the mode.

These assumptions should be considered when interpreting the results, particularly where a blank value does not necessarily confirm a person's status.

## Age Distribution

The chart below illustrates the distribution of ages
in the census dataset.

<img width="822" height="581" alt="age distribution" src="https://github.com/user-attachments/assets/cfa18279-6e5c-4d0f-8d11-3543ece613da" />


## Gender Distribution

The chart below illustrates the gender distribution 
in the census dataset.
<img width="737" height="571" alt="Screenshot 2026-10-14 133916" src="https://github.com/user-attachments/assets/e0d837bb-f042-429d-bdcb-7323f7e375a3" />



## Key Findings

The dataset contains 7,827 records.

- Residents aged 0–17 account for approximately 23.70% of the population.
- Residents aged 5–17 account for approximately 17.61%.
- The dataset records 489 university students, approximately 6.25% of the population.
- The analysis considers education and transport infrastructure as possible community investment priorities.

## Recommendations

The analysis recommends prioritising educational facilities in response to the size of the school-age population. It also considers the potential value of a train station, subject to further investigation of transport demand, feasibility, accessibility, and cost.

These recommendations are based on the available mock census data and should not be interpreted as proof of actual transport usage or infrastructure feasibility.

## Limitations

- The dataset is mock census data and may not represent an actual community.
- Missing-value handling involves assumptions that may affect interpretation.
- Census demographics alone cannot establish the financial or practical feasibility of major infrastructure projects.


Data Analytics | Machine Learning | Python | Data Visualisation
