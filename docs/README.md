## 99% of U.S. Deportees Over Four Years Came From Latin America

## Goals
This project aims to answer key questions:

*How many people were deported from the United States between 2020 and 2024.

*Which countries they came from.

*What legal grounds were used for these deportations.

*What patterns emerge from the data.

## Findings
*More than half a million people were deported from the U.S. between October 2020 and September 2024.

*Ninety‑nine percent of all deportees came from Latin American countries, showing a clear regional pattern.

*Mexico alone accounted for more than 44 percent of all removals.

*Most deportations were related to immigration or administrative issues, and only about one‑third of deportees had criminal convictions.

## Data Collection Process
Data was collected from the ICE Enforcement and Removal Operations Statistics website.

The dataset was downloaded from the Excel file linked at the bottom of the main page, which contains all available removal records. I selected and downloaded the sheet containing information about removals (the formal term used by ICE for deportations).

## Data Analysis Process

The analysis was conducted in Python using Pandas inside a Jupyter Notebook.

Main steps included:

*Converting the “Month-Year” column into a proper datetime format using pd.to_datetime.

*Splitting month and year into separate columns.

*Grouping removals by year using groupby and sum, since removal counts vary per row.

*Exporting results as CSV files for visualization in Datawrapper.

*Using unique() and groupby() to identify:

Total number of countries represented

Countries with the highest number of deportees

Creating a subset of Latin American countries and calculating their percentage of total removals.

Grouping by allegation category to analyze the legal grounds for deportation.

Live Story
https://laracastelo.github.io/Deportation/
