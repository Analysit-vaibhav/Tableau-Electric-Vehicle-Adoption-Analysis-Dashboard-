# Electric Vehicle Data Analysis

## Overview
The **Electric Vehicle Data Analysis** project explores the state of the electric vehicle (EV) market, focusing on adoption trends, key metrics like BEV (Battery Electric Vehicle) and PHEV (Plug-in Hybrid Electric Vehicle) market share, and regional variations in EV adoption. This project aims to provide insights into the current EV landscape and help guide policymaking, manufacturing, and consumer decisions to accelerate EV adoption.

## Data Source
- **Dataset Information**: 
  - The dataset includes over **119,917** electric vehicle registrations across various regions, covering key attributes such as vehicle type (BEV/PHEV), model, year, state, city, CAFV eligibility, and more.

  
- **Data Access**: 
  - If the dataset is shared publicly or within the repository, you can access it directly via the link provided. If not, specific data access instructions should be mentioned here.

## Tools Used
- **Tableau**: The primary tool used for data visualization, dashboard creation, and interactive analysis.
- **Other Tools**: 
  - **Excel/SQL** for data cleaning, preprocessing, and transformation tasks before importing into Tableau.
  - **Geospatial Analysis Tools**: If used, such as ArcGIS or other mapping tools for geographic insights and visualizations.

## Key Findings / Insights
- **Market Dominance of BEVs**: Over **83.1%** of electric vehicles in the dataset are **Battery Electric Vehicles (BEVs)**, showcasing strong consumer preference for fully electric vehicles over hybrids.
- **Tesla's Market Share**: **Tesla** leads the EV market with **57.49%** of the registrations among the top 7 EV brands.
- **CAFV Eligibility**: **47.06%** of vehicles have an unknown **CAFV eligibility status**, which may limit the effectiveness of clean fuel vehicle programs.
- **Regional Adoption Variations**: The analysis reveals that EV adoption varies significantly by region, with certain areas showing higher penetration rates, while others remain underserved in terms of EV infrastructure.

## Visualizations
### 1. **Overview Dashboard**
   - **Key Elements**: Displays the total count of electric vehicles, breakdown by BEV and PHEV market share, and other key metrics such as average electric range.
   - **Charts**: 
     - **Pie Chart** showing the distribution of BEVs vs. PHEVs.
     - **Bar Charts** for top EV models and market shares.
     - **Line Chart** displaying EV registration trends over the past 5 years.

### 2. **Regional Adoption Map**
   - **Key Elements**: A **choropleth map** visualizing EV adoption across different states and cities.
   - **Insights**: Highlights regions with low EV adoption and identifies potential opportunities for targeted infrastructure investment and policy incentives.

### 3. **CAFV Eligibility Analysis**
   - **Key Elements**: Pie chart and bar charts showing the distribution of vehicles by CAFV eligibility.
   - **Insights**: Reveals the percentage of vehicles eligible for Clean Alternative Fuel Vehicle (CAFV) programs and identifies gaps in data that need to be addressed.

## Key Metrics
- **Total Vehicles**: **119,917** electric vehicles registered.
- **Total BEV Vehicles**: **83.1%** of total vehicles are BEVs.
- **Total PHEV Vehicles**: **16.9%** of total vehicles are PHEVs.
- **Average Electric Range**: **77.71 miles**.
- **CAFV Eligibility**: **45.05%** eligible, **47.06%** unknown eligibility status.

## Real-Life Insights & Implications
### Policymakers:
- **Targeted Incentives**: Focus EV adoption incentives on regions with lower adoption rates to accelerate market growth.
- **Charging Infrastructure**: Invest in building a comprehensive and accessible charging infrastructure to mitigate range anxiety and improve EV adoption.
- **CAFV Program Improvements**: Streamline data collection and eligibility processes to enhance the effectiveness of CAFV programs.

### Manufacturers:
- **Battery Technology**: Invest in further innovations in battery life, range, and charging speed to enhance the consumer EV experience.
- **Affordable Models**: Expand the availability of affordable BEVs to make EVs more accessible to a broader audience.
- **Charging Solutions**: Develop home and public charging solutions to accommodate the increasing number of EVs.

### Consumers:
- **Range Anxiety**: With increasing average ranges of EVs, range anxiety is likely to reduce, making EVs more feasible for daily commutes and long trips.
- **Cost of Ownership**: Consumers should consider the total cost of ownership, including incentives, charging costs, and long-term savings on maintenance.
- **Government Incentives**: Take advantage of government subsidies or tax incentives to make EV ownership more affordable.

## Next Steps
- **Data Enrichment**: Incorporate additional data points such as battery capacity, vehicle age, and charging station availability to refine the analysis and gain deeper insights.
- **Trend Analysis**: Conduct further analysis on the projected growth of EV adoption, battery advancements, and policy changes to forecast future market trends.
- **Geospatial Deep-Dive**: Perform detailed geospatial analysis to identify key drivers of EV adoption and develop region-specific strategies.

## How to Use the Project

### Installation / Setup:
1. Clone this repository to your local machine.
2. Open the Tableau Workbook file (`.twb` or `.twbx`) to view and interact with the dashboard.
3. If applicable, update the data connection settings if using an external data source.

### Interacting with the Dashboard:
- **Filters**: Use filters to adjust the data by year, vehicle type, region, etc.
- **Tooltips**: Hover over visual elements to reveal additional details like exact numbers, percentages, or key insights.
- **Drill-Downs**: Click on regions or categories to drill down into more detailed visualizations and data.
- **TopN Parameter**: Use the **TopN parameter** to control how many top items are displayed in bar charts or tables.

#
