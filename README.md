# Finding-Crime-Rate-in-Montreal-using-Actes-criminels

# Montreal Crime Analysis

This project analyzes the distribution and nature of crime in Montreal City using data provided by the Service de police de la Ville de Montréal (SPVM). The analysis includes visualizations of crime incidents across different neighborhoods and police districts, and it aims to answer several key questions about crime patterns in the city.

## Project Overview

The primary objective of this project is to provide insights into crime trends in Montreal by analyzing the provided dataset and visualizing the results. This includes identifying the most common crimes, the time of day when most incidents occur, and the police precincts that handle the most and least complaints.

## Key Questions Addressed

1. **Top 3 Prevalent Crimes**: What are the top 3 most common crimes or offenses committed in Montreal City?
2. **Crime Timing**: During what part of the day do most crime incidents occur?
3. **Top 5 Police Precincts**: Which are the top 5 police precincts (PDQs) with the most crime complaints?
4. **Least Crime Complaints**: Which are the top 3 PDQs with the least crime complaints?
5. **High Crime Neighborhoods**: Which neighborhoods recorded the highest crime incidents, and what types of crimes are prevalent in these areas?
6. **Murder Cases**: Which neighborhood has the most cases of murder?

## Data Description

The project uses the `actes-criminels.csv` dataset, which contains the list of criminal acts recorded by the SPVM. The dataset includes the following key columns:

- **CATEGORIE**: Type of criminal event (e.g., theft, robbery, murder).
- **DATE**: Date the event was reported.
- **QUART**: Time of day the event was reported (day, evening, night).
- **PDQ**: Police precinct number covering the event location.
- **LATITUDE** and **LONGITUDE**: Geographical coordinates of the event.

Additionally, the `limitespdq.geojson` file contains the geographical boundaries of each police precinct in Montreal.

## Methodology

The analysis involves:

1. **Data Preparation**: Cleaning and structuring the data to ensure accurate analysis.
2. **Geospatial Analysis**: Mapping crime incidents to specific neighborhoods and police precincts using geographical coordinates.
3. **Visualization**: Creating maps and charts to visualize crime patterns across the city.
4. **Statistical Analysis**: Drawing conclusions based on the data, answering the key questions, and extracting additional insights.

## Tools and Technologies

- **Python**: For data analysis and visualization.
- **Pandas**: For data manipulation
