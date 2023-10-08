# Coffee-Sales-Excel-Interactive-Dashboard-Project

<img width="964" alt="image" src="https://github.com/stefanmills/Coffee-Sales-Excel-Interactive-Dashboard-/assets/24477861/eb9fbbad-446c-45f2-859c-82724c5cdc79">

Welcome to the Coffee Sales Dashboard Portfolio Project repository. This project demonstrates my Excel skills in data analysis and visualization. The objective is to create an interactive dashboard that provides insights into coffee sales data.

Data: 

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Techniques Used](#techniques-used)
- [Usage](#usage)

## Project Overview

In this project, we have undertaken a series of tasks to develop a Coffee Sales Dashboard in Excel. Here's a summary of the key steps:

1. **XLOOKUP for Customer Details:**
   - We utilized the XLOOKUP function to retrieve customer details based on CustomerID.

2. **Locking Values:**
   - We used the `$` symbol in formulas to lock specific values for precise referencing.

3. **Handling Missing Emails:**
   - To address cases where customer emails were missing, we applied an IF statement with XLOOKUP to return blanks when necessary.

4. **XLOOKUP for Country:**
   - The Country column (Column H) was populated using XLOOKUP to find values in the Customers table.

5. **XLOOKUP for Columns I-L:**
   - Columns I through L were populated with data using XLOOKUP, referencing the Products table.

6. **Calculating Total Sales:**
   - Column M represents the product of Quantity and Unit Price, providing total sales.

7. **Custom Coffee and Roast Type Names:**
   - Columns N and O (Coffee Type Name and Roast Type Name) were enriched with descriptive names using the IFS function.

8. **Date and Size Formatting:**
   - We formatted the Date column (Column B) as "dd-mmm-yyyy" for improved readability.
   - The Size column received a "kg" suffix using a custom cell format: `0.0"kg"`.

9. **Currency Formatting:**
   - Unit Price and Sales columns were formatted with the appropriate currency symbol.

10. **Loyalty Card Lookup:**
    - We used XLOOKUP to determine whether customers have a loyalty card, referencing the Customer workbook.

11. **Duplicate Removal:**
    - Duplicates were eliminated from the entire table, ensuring data integrity.

12. **Pivot Table Creation:**
    - We generated a pivot table for data summarization and analysis.

13. **Charts, Timelines, and Slicers:**
    - Interactive elements such as charts, timelines, and slicers were incorporated to enhance data exploration.

14. **Report Interactivity:**
    - We established a report connection, enabling all timelines and slicers to influence the behavior of charts and visuals.

15. **Dashboard Duplication:**
    - The dashboard was replicated to match the provided image, maintaining structure and functionality.

## Features

- Interactive Coffee Sales Dashboard.
- XLOOKUP for data retrieval.
- Custom formatting for enhanced data presentation.
- Pivot table for data summarization.
- Dynamic charts, timelines, and slicers for exploration.
- Data duplication handling.
- Loyalty card status xlookup.

## Techniques Used

- Excel formulas and functions.
- Pivot tables and charts.
- Data formatting and customization.
- Interactive dashboard design.
- Data deduplication.

## Usage

The Coffee Sales Dashboard is user-friendly and offers an array of interactive tools to analyze coffee sales data effectively. Utilize the provided timelines, slicers, and charts to gain insights into the data.


