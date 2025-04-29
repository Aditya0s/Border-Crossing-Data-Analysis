# Border Crossing Entry Data Analysis

## 1. Introduction

Border crossing data represents the count of people, vehicles, and goods entering and exiting a country through authorized ports. Analyzing this data can help understand international traffic flow, port utilization, and trends in travel or trade. This project aims to visualize the trends and patterns in U.S. border crossings through an interactive dashboard in Excel.

## 2. Source of Dataset

The dataset used for this project is titled “Border Crossing Entry Data,” sourced from the U.S. government’s open data platform ([Transportation Data Portal](https://catalog.data.gov/dataset/border-crossing-entry-data-683ae)). It includes data on the number of crossings, categorized by state, port name, type of crossing (e.g., trucks, pedestrians), date, and geographical coordinates (latitude and longitude).

## 3. Dataset Preprocessing

The dataset underwent the following preprocessing steps:

- Removed duplicate records.
- Checked for and handled missing/null values.
- Standardized text formatting (proper case, trimmed spaces).
- Converted date format to standard `yyyy-mm`.
- Formatted the data as a table in Excel for dynamic referencing.

## 4. Analysis on Dataset (for Each Objective)

### **Objective 1: Trend Analysis of Border Crossings**
- **Description**: Analyzed the overall trend of border crossings over time to observe patterns like growth, decline, or seasonal fluctuations in border activity.
- **Method**: Summarized the dataset based on Date and Value, grouped by month and year.
- **Results**: Displayed trends with a Line Chart, and used slicers for interactive filtering of crossing types.

### **Objective 2: Comparison of US-Canada vs. US-Mexico Border Traffic**
- **Description**: Compared the total number of border crossings between the US-Canada and US-Mexico borders.
- **Method**: Grouped the data by the “Border” column and summarized crossing values.
- **Results**: Visualized the comparison with a Column Chart, showing the higher crossing volumes at the US-Mexico border.

### **Objective 3: State-wise Border Crossing Analysis**
- **Description**: Analyzed border crossings by state to identify which U.S. states experience the most traffic.
- **Method**: Grouped the data by the “State” column and calculated the total crossings per state.
- **Results**: Created a heatmap and bar chart to highlight the busiest states, with Texas and California showing the highest numbers.

### **Objective 4: Top Ports for Border Crossings**
- **Description**: Identified the busiest border ports across the United States to understand port-level traffic.
- **Method**: Grouped by “Port Name” and calculated the total crossings for each port.
- **Results**: Sorted and visualized the top 10 busiest ports using a bar chart.

### **Objective 5: Geospatial Visualization with 3D Map**
- **Description**: Created a geographical visualization of the border crossing data using Excel’s 3D Maps tool.
- **Method**: Plotted ports using latitude and longitude coordinates, with crossing volumes represented by column height.
- **Results**: Generated a 3D map showing traffic intensity at each port, with hotspots like Laredo and El Paso standing out.

## 5. Conclusion

The dashboard provides a comprehensive view of border crossing trends in the U.S. from 1996 to 2025. It highlights a decline in border crossings post-2020, likely due to the COVID-19 pandemic and related restrictions. The analysis reveals that the US-Mexico border consistently sees more traffic than the US-Canada border. Additionally, Texas and California are the leading states for border activity, with ports like San Ysidro, El Paso, and Laredo handling the most traffic.

## 6. Future Scope

- Automate data updates via Power Query.
- Integrate forecasting tools using Power BI or advanced Excel functions.
- Build a real-time dashboard using Python or web tools.
- Add anomaly detection for identifying suspicious border crossing surges.

## 7. Installation & Usage

### Prerequisites:
- Microsoft Excel (for the dashboard and analysis)
- Access to the dataset (sourced from [Transportation Data Portal](https://catalog.data.gov/dataset/border-crossing-entry-data-683ae))

### Steps:
1. Download the "Border Crossing Entry Data" dataset from the U.S. government’s open data platform.
2. Open the Excel file and explore the various analyses and interactive features like slicers and charts.

