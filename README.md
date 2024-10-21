

# Store Sales Data Analysis - Excel Project

## Project Overview

This project focuses on performing data analysis for **Vrinda Store**, a fictional retail store, using **Microsoft Excel**. The goal is to derive insights into sales trends, customer demographics, and order fulfillment. The project includes key steps such as **data cleaning**, **data processing**, and **visualization** to create an interactive dashboard that enables easy analysis of various metrics like sales by category, region, and channel.

## Dataset Overview

The dataset includes various columns like product categories, order details, sales amount, customer demographics (age and gender), and order status. The analysis was done on:

- **Product Categories**: Blouse, Bottom, Ethnic Dress, etc.
- **Months**: January, February, March (and more)
- **Sales Channels**: Ajio, Amazon, Flipkart, Meesho
- **Gender**: Sales by Men vs Women
- **Age Groups**: Adult, Senior, Teenager
- **Order Status**: Delivered, Cancelled, Returned, Refunded
- **Sales Amount**: Total sales generated in different periods

## Data Cleaning & Preparation

Before creating the dashboard, the raw dataset underwent several cleaning steps to ensure data accuracy and consistency. Here are the key data cleaning steps:

1. **Removing Duplicates**:
   - The dataset was checked for duplicate entries, especially in order IDs and customer data, and duplicates were removed to avoid double counting in analysis.
   
2. **Handling Missing Data**:
   - Missing data in key columns like sales amount, order status, and customer details were addressed.
   - **Sales Amount**: For any missing sales data, averages from similar categories or months were used to estimate values.
   - **Order Status**: Missing or blank statuses were filled using the most likely status based on historical trends.

3. **Data Formatting**:
   - Standardized date formats (dd-mm-yyyy) and ensured consistency in naming conventions across product categories and sales channels.
   - Converted all currency data to a uniform format to ensure consistency in calculations.

4. **Removing Outliers**:
   - Sales and order amounts significantly different from the general trend were reviewed. If these were deemed data entry errors, they were either corrected or removed.

5. **Category Mapping**:
   - Mapped product sub-categories into broader categories like Blouse, Bottom, Ethnic Dress, to make analysis easier.

6. **Creating Calculated Columns**:
   - New columns were added to facilitate analysis:
     - **Month**: Extracted from the date column to facilitate monthly analysis.
     - **Total Sales**: Calculated based on unit prices and quantities sold.
     - **Order Completion Time**: Calculated for measuring the average delivery time.

## Data Processing

After the data cleaning phase, the data was processed to create summary statistics and visual insights. This included:

1. **Using Pivot Tables**:
   - Created **pivot tables** to summarize data by categories, months, and channels. This allowed for quick aggregation of data like total sales, orders, and profits.

2. **Creating Visualizations**:
   - Various Excel charts (bar, line, pie charts) were used to represent key data insights:
     - **Monthly Sales Trends**: A line chart to show sales performance over the months.
     - **Sales by Gender**: A pie chart comparing sales contributions from men and women.
     - **Order Status**: A breakdown of orders by their status (delivered, returned, canceled).
     - **Age vs Gender Orders**: A bar chart showing order distributions across different age groups and genders.

3. **Slicer Implementation**:
   - **Slicers** were added to the dashboard for interactive filtering, allowing users to explore data by **Month**, **Category**, and **Channel**.

4. **Trend Analysis**:
   - Compared performance across time periods (e.g., monthly sales) and looked for trends such as seasonality or changes in customer preferences.

## Key Insights from the Dashboard

### 1. **Orders vs Sales**
   - Line and bar chart combination showing the comparison between the number of orders and total sales month by month.
   - **Insight**: Shows if the number of orders is aligned with revenue growth.

### 2. **Sales by Gender**
   - Pie chart highlighting sales distribution:
     - **Women**: 58%
     - **Men**: 42%
   - **Insight**: The store’s customer base skews slightly towards women.

### 3. **Order Status Breakdown**
   - Pie chart showing the status of orders:
     - **Delivered**: 55%
     - **Cancelled**: 3%
     - **Returned**: 2%
   - **Insight**: The majority of orders are successfully delivered.

### 4. **Top 6 Performing Regions**
   - Bar chart showing the regions that contribute the most to total sales:
     - **Top region**: Uttar Pradesh with 0.06M in sales.
   - **Insight**: Focus marketing efforts on the top-performing regions.

### 5. **Order Age vs Gender**
   - Bar chart displaying order breakdown by age group and gender:
     - Adults contribute the most to sales (29% women, 19.77% men).
   - **Insight**: Adults are the largest customer group, but teenagers show potential for growth.

### 6. **Orders by Sales Channel**
   - Pie chart showing 100% of orders were from the **Meesho** channel (filtered data used).
   - **Insight**: Different channels can be filtered using slicers to track sales distribution across platforms.

## Tools & Technologies

- **Microsoft Excel**:
  - **Pivot Tables**: Used for data aggregation and summary.
  - **Slicers**: Added for filtering data by category, month, and sales channel.
  - **Charts & Graphs**: Used to visualize sales trends, order statuses, and demographics.
  
## Steps to Reproduce

To reproduce the analysis and visualizations:
1. **Open the Excel file** with the provided dataset.
2. **Review the "Sales" sheet**, where the raw data is stored.
3. Use **Pivot Tables** to create aggregated views of the data.
4. Create **charts** to visualize sales trends, order statuses, and more.
5. Implement **slicers** for interactive filtering based on user requirements (e.g., by Category or Channel).
6. Generate a **final report** in the "Report" sheet with all key visualizations summarized.

## Conclusion

The **Vrinda Store Data Analysis** project demonstrates how Excel can be used for robust data analysis, providing insights into sales trends, customer demographics, and order fulfillment. By using interactive features like slicers and visualizations, stakeholders can easily explore data and make informed business decisions.

![image](https://github.com/user-attachments/assets/3c167126-064b-445b-a672-cc46c5f51071)
