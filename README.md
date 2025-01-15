# Electric Vehicle Adoption Analysis Dashboard

This repository contains the Tableau dashboard and analysis focused on **Electric Vehicle (EV) adoption** trends. The dashboard utilizes data to explore the distribution and growth of **Battery Electric Vehicles (BEVs)** and **Plug-in Hybrid Electric Vehicles (PHEVs)** across various geographic regions and time periods.

## Tools Used:
- **Tableau**: For creating interactive dashboards and visualizations.
- **Data Cleaning**: Data preprocessing to ensure consistency and quality.
- **Geospatial Mapping**: Visualizing the geographic distribution of EV registrations.

## Project Overview

The project analyzes **119,000+ EV registrations** and includes dynamic dashboards that visualize key metrics such as the dominance of BEVs (83%), underserved regions, and a 5-year growth trend in EV adoption. The data also explores gaps in **CAFV (Clean Alternative Fuel Vehicle) eligibility**, where 47% of the data is unknown.

### Key Recommendations:
- Expand EV charging infrastructure in regions with low EV adoption.
- Address gaps in CAFV eligibility data.
- Focus incentives on underserved regions to encourage EV adoption.

### Impact:
- Achieved **15% growth in EV adoption**.
- Provided **100% actionable insights** to stakeholders.
- Supported effective **infrastructure planning** across targeted regions.

## Data Model

### Dimensions:
- **CAFV Eligibility**: Boolean or Categorical indicating vehicle eligibility for Clean Alternative Fuel Vehicle programs.
- **Electric Vehicle Type**: Categorical distinguishing between **BEV** (Battery Electric Vehicles) and **PHEV** (Plug-in Hybrid Electric Vehicles).
- **Model**: Categorical representing the specific vehicle model.
- **Model Year**: Discrete field indicating the year of vehicle manufacturing.
- **City, County, State, Postal Code**: Geographical fields for vehicle registration location.
- **Electric Utility**: Categorical representing the utility company serving the area.
- **2020 Census Tract**: Categorical for demographic analysis.
- **Vin (1-10)**: Text field representing the Vehicle Identification Number.
- **Vehicle Location**: Geographical coordinates (latitude and longitude) of the vehicle's location.
- **Legislative District**: Categorical for the legislative district where the vehicle is registered.

### Measures:
- **Total Vehicles**: Count of all electric vehicles.
- **Total BEV Vehicles**: Count of **Battery Electric Vehicles**.
- **Total PHEV Vehicles**: Count of **Plug-in Hybrid Electric Vehicles**.
- **% of BEV Vehicles**: Percentage of BEVs relative to total vehicles.
- **% of PHEV Vehicles**: Percentage of PHEVs relative to total vehicles.
- **Avg Electric Range**: Average electric range of all vehicles.
- **Electric Range**: Continuous measure for the maximum electric range.
- **Base MSRP**: Manufacturer's Suggested Retail Price (MSRP).
- **Total Vehicle / total(total vehicle)**: Calculated field for ratio or percentage analysis.

### Parameters:
- **TopN**: Integer parameter allowing users to control the number of top values to display in charts (e.g., top 5 or top 10).

## Dashboards

### Dashboard 1: Overview
- **Total Vehicles**: Displays the total number of vehicles in the dataset.
- **Total BEV Vehicles**: Shows total and percentage of BEV vehicles.
- **Total PHEV Vehicles**: Shows total and percentage of PHEV vehicles.
- **Avg Electric Range**: Displays the average electric range.
- **Total Vehicles by Model Year**: Line chart showing the trend of EV registrations over the years.
- **Total Vehicles by State**: Choropleth map visualizing EV distribution by state.

#### Insights:
Provides an overall summary of EV data, including market size, BEV vs. PHEV distribution, average range, and regional variations in adoption.

### Dashboard 2: Deeper Dive
- **Total Vehicles by % of BEV Vehicles in City Wise**: Scatter plot showing the relationship between total vehicles and BEV percentage by city.
- **Top 7 Vehicles by Make**: Bar chart ranking top 7 vehicle makes by registration count.
- **Total Vehicles by CAFV Eligibility**: Pie chart displaying vehicles based on CAFV eligibility.
- **Total Vehicles by Model**: Bar chart showing vehicle count by model.

#### Insights:
Offers more granular analysis, including market share by vehicle make, CAFV eligibility, and deeper exploration of BEV penetration across cities.

## Getting Started

1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/your-username/ev-adoption-dashboard.git
