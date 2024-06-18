# India Census Data Visualization (2011)

This project involves visualizing the India Census data of 2011 using Power BI. The visualizations include population and literacy rates for males and females, district-wise and state-wise, utilizing various chart types such as bar charts, pie charts, and slicers for interactive filtering.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Requirements](#data-requirements)
- [Visualizations](#visualizations)
  - [Population Charts](#population-charts)
  - [Literacy Rate Charts](#literacy-rate-charts)
  - [Literates by District and State](#literates-by-district-and-state)
- [Steps to Create the Visualizations](#steps-to-create-the-visualizations)
- [Usage](#usage)



## Project Overview
This project aims to provide insights into the demographic and literacy characteristics of the Indian population as per the 2011 Census. The dashboard includes:
- District-wise male and female population with respect to states.
- Literacy rates with respect to districts of each state.
- Female and male literates with respect to district codes and states.

## Data Requirements
To create this Power BI dashboard, you need the following data from the India Census 2011:
- District-wise population data segregated by gender.
- Literacy rates for each district.
- Data on literates (both male and female) with district codes and state names.

## Visualizations

### Population Charts
- **Bar Chart**: Shows the male and female population for each district within a state.
- **Slicer**: Allows filtering by state to view the population data for districts within a specific state.

### Literacy Rate Charts
- **Bar Chart**: Displays literacy rates for each district within a state.
- **Slicer**: Provides the ability to filter literacy rates by state and set a range for literacy rates.

### Literates by District and State
- **Pie Chart**: Illustrates the proportion of male and female literates within a district.
- **Slicer**: Enables filtering by district codes and states to focus on specific regions.

## Steps to Create the Visualizations

### 1. Prepare Your Data
1. **Collect Data**: Download the India Census 2011 data, ensuring it includes district-wise male and female population, literacy rates, and literates with district codes and states.
2. **Clean Data**: Ensure the data is formatted correctly and all necessary columns are present.

### 2. Load Data into Power BI
1. Open Power BI Desktop.
2. Load the data by clicking on "Get Data" and selecting the appropriate data source (e.g., Excel, CSV).

### 3. Data Transformation
1. Open Power Query Editor by clicking on "Transform Data".
2. Filter and transform the data as needed, ensuring all required fields are present and correctly formatted.

### 4. Create Visualizations

#### Population Charts
1. **Bar Chart**:
   - Add a bar chart to the report.
   - Set the axis to "District".
   - Set the values to "Male Population" and "Female Population".
   - Add a slicer for "State".

#### Literacy Rate Charts
1. **Bar Chart**:
   - Add a bar chart to the report.
   - Set the axis to "District".
   - Set the values to "Literacy Rate".
   - Add a slicer for "State" and a numeric range slicer for "Literacy Rate".

#### Literates by District and State
1. **Pie Chart**:
   - Add a pie chart to the report.
   - Set the legend to "Gender" (Male Literates, Female Literates).
   - Set the values to the respective literate counts.
   - Add slicers for "District Code" and "State".

### 5. Customize and Publish
1. Customize the charts for better readability and aesthetics.
2. Publish the dashboard to Power BI Service if you wish to share it.

## Usage
1. **Clone the Repository**: 
   ```bash
   git clone https://github.com/Coderconer/Power-Bi-India-Census.git
