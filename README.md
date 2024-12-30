# Coffee Shop Analysis Project Documentation  

![Dashboard](https://github.com/user-attachments/assets/6a133c3f-2a0d-4795-87fe-15205d1b0468)  

## Project Overview  
This project analyzes data from a coffee shop to uncover trends, optimize operations, and provide actionable insights. The original dataset contained only the **Raw Data** sheet, and I created additional sheets and features to enhance its usability and insights.  

## Objectives  
1. Organize and clean the raw data.  
2. Analyze coffee shop data to extract meaningful insights.  
3. Create interactive and visually appealing dashboards.  
4. Provide actionable recommendations to improve coffee shop operations.  

## Features  

### 1. **Data Cleaning**  
- Cleaned the **Raw Data** sheet by:  
  - Ensuring there were no duplicate entries.  

### 2. **Clean Data Sheet**  
- Created a new sheet called **Clean Data** by copying the original **Raw Data** sheet.  
- Added the following new columns:  
  - **day_of_the_week**: Extracted from the `transaction_date` column using the `TEXT` function.  
  - **month**: Extracted from the `transaction_date` column using the `TEXT` function.  
  - **hour**: Extracted from the `transaction_time` column using the `HOUR` function.  

### 3. **Pivot Tables**  
- Created multiple PivotTables in a new sheet named **Pivot Tables** to summarize and analyze the data.  
- Used these tables to derive insights for the dashboard.  

### 4. **Interactive Dashboard**  
- Built a dashboard in the **Dashboard** sheet to visualize key metrics and trends using:  
  - **PivotTable Data**: Integrated summaries and insights from the Pivot Tables sheet.  
  - **Charts**: Included KPI cards, line graphs, a Table and Bar graphs for better data representation.  
  - **Slicers**: Added slicers to enable dynamic filtering of data.  

### 5. **Recommendations**  
- Created a **Recommendations** sheet to provide actionable insights based on the analyzed data.  

## Deliverables  
1. **Raw Data Sheet**  
   - Contains the original dataset as provided, cleaned to remove duplicates.  

2. **Clean Data Sheet**  
   - A cleaned and structured version of the raw data with additional columns for analysis.  

3. **Pivot Tables Sheet**  
   - Summarized data using multiple PivotTables for deeper insights.  

4. **Dashboard Sheet**  
   - A visually appealing and interactive dashboard summarizing the analysis.  

5. **Recommendations Sheet**  
   - A list of actionable recommendations derived from the analysis.  

## Key Insights  
- Identified peak hours, days, and months for coffee shop activity both overall and for every location.  
- Highlighted customer behavior trends to optimize operations.  
- Recommendations to improve sales and customer satisfaction.  

## Tools and Techniques  
- **Excel Functions**: Used various excel functions to add columns.
- **Data Cleaning**: Removed duplicates and standardized formats.  
- **Data Visualization**: Charts, slicers, and conditional formatting.  
- **PivotTables and PivotCharts**: For dynamic analysis and visualization.  

## Challenges and Solutions  
- **Challenge**: Extracting meaningful insights from raw data.  
  - **Solution**: Created derived columns and used PivotTables for detailed analysis.  
- **Challenge**: Designing a user-friendly and insightful dashboard.  
  - **Solution**: Focused on clear layouts and interactive features.  

## Future Improvements  
- Add advanced analytics, such as forecasting or trend analysis.  
- Automate data updates using Power Query or VBA.  
- Expand recommendations with additional data points or external benchmarks.  

## Conclusion  
This coffee shop analysis project highlights my ability to transform raw data into actionable insights through effective data analysis and visualization in Excel. It showcases my skills in data cleaning, PivotTables, and dashboard creation, along with providing data-driven recommendations to improve business operations. 
