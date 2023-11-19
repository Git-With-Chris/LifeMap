# Death Rate Explorer (2019) 🪦

## Overview

The **Death Rate Tracker (2019) Shiny App** is an interactive data visualization tool built using Shiny, Leaflet, Plotly, and other R packages. It allows users to explore and analyze death rates across different countries, age groups, and causes of death for the year 2019.

## Features

1. **Death Rate Map:** A choropleth map visualizing death rates across countries. The map provides a color-coded representation of death rates, with tooltips displaying detailed information for each country. Hover over countries to view detailed information.

2. **Breakdown by Age and Country:** Users can select specific age groups and countries to view a bar chart (Plotly) illustrating the breakdown of total deaths by age and cause. The chart dynamically updates based on user selections.

3. **Reference Information:** The app includes a button to access references providing sources for the data used in the app. Users can click the "References" button to view this information.

4. **Summary Statistics:** The app presents summary statistics, including the average death rate, the country with the highest death rate, and the top cause of death.

## Data Sources

The app utilizes death rate data for the year 2019 from various sources, including World Bank and Our World in Data. The data is categorized by age group and cause of death.

## Demo

![Demo](images/Demo.png)

## Usage

1. Clone this repository to your local machine using the following command:

```bash 
git clone https://github.com/your-username/death-rate-tracker.git  
```
2. Open RStudio.
3. Set your working directory to the location where you cloned the repository.
4. Open both ui.R and server.R files in RStudio.
5. Click the "Run App" button to launch the Shiny app.

## Dependencies

The app relies on the following R packages:
- Shiny
- Shinydashboard
- Shinyalert
- Tidyverse
- SF
- Leaflet
- Ggthemes
- Plotly

To run the app locally, make sure you have R installed on your machine. Install the required packages by running the following commands:

```R
install.packages(c("shiny", "shinydashboard", "shinyalert", "tidyverse", "sf", "leaflet", "ggthemes", "plotly"))
```

## Acknowledgments

This app was developed as a part of a project to visualize and analyze death rate data for the year 2019. The data sources are credited in the references section.
