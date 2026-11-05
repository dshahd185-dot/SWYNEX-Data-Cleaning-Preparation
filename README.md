# SWYNEX-Data-Cleaning-Preparation
Data cleaning and preparation project - SWYNEX internship Task 1
# Online Store Data Cleaning – Project Summary

In this project, I worked on cleaning and preparing an online store orders dataset using Python and the Pandas library.

The main goal was to improve data quality and make the dataset ready for analysis and dashboard creation.

### Data Cleaning Steps

1. **Data Inspection:** Checked the dataset structure, column names, data types, missing values, and duplicate records.

2. **Handling Missing Values:** Identified missing values and filled them using suitable methods, such as mean, median, mode, or "Unknown", depending on the column.

3. **Text Standardization:** Cleaned text values by removing extra spaces and correcting inconsistent entries.

4. **Handling Invalid Values:** Identified and corrected invalid numerical values, such as negative prices and quantities.

5. **Handling Zero Values:** Reviewed zero values in important numerical columns and replaced them when appropriate using related columns.

6. **Outlier Treatment:** Reviewed unusual numerical values and corrected some unrealistic values using available order information.

7. **Date Conversion:** Converted the Order Date column into a proper datetime format and handled invalid dates.

8. **Recalculating Total Amount:** Recalculated missing or zero total amounts using the unit price, quantity, and discount percentage.

9. **Final Data Validation:** Checked the dataset again to review missing values, duplicates, data types, negative values, and numerical statistics.

### Final Result

After completing the cleaning process, the dataset became more consistent and suitable for further analysis.

The cleaned dataset was exported to an Excel file named:

**Online_Store_Cleaned.xlsx**

It is now ready for use in Excel PivotTables, charts, and interactive dashboards.
## Files
- task1/Messy_Online_Store_Orders.csv : raw data
- task1/Online_Store_Cleaned.xlsx : cleaned data
- Online_Store_Data_Cleaning.ipynb : cleaning code (Python/Pandas)
