# Custom Calendar by Akvelon Feature Validation Findings

## Overview

Custom Calendar by Akvelon is a PowerBI custom visual designed for displaying daily data from various sources such as Excel sheets, CSVs, SQL, and more. It presents data in a traditional calendar format, displaying data proportionally within each day of the calendar. This visual is particularly useful for visualizing payroll, attendance, traffic, project hours, and other data that can be reported daily.

## Validation Sources

1. [Microsoft AppSource - Custom Calendar by Akvelon](https://appsource.microsoft.com/en-sg/product/power-bi-visuals/WA104381179)
2. [Akvelon Blog - Visualize Your Data Set in the Power BI Custom Calendar](https://akvelon.com/visualize-your-data-set-in-the-power-bi-custom-calendar/)

## Feature Support Summary

Based on the original matrix and validation against official documentation:

- Total features: 128
- Features supported (y): 5
- Features not supported (n): 92
- Features with no data (NaN): 31

## Key Features Confirmed

The following key features were explicitly confirmed in the documentation:

1. **Week** - The visual supports weekly view and data organization
2. **Week Start Day** - Users can customize which day starts the week
3. **Fixed and Relative Start/End Dates** - Supports both fixed date ranges and relative date ranges
4. **Multiple Metrics** - Supports multiple numbers of metrics within the calendar
5. **Cross Selection** - Allows for cross-selection functionality with other visuals

## Features Not Supported

According to the matrix, Custom Calendar does not support many advanced filtering and selection features. This aligns with the documentation which shows Custom Calendar is focused specifically on providing a calendar-based data visualization with basic customization capabilities rather than advanced filtering functionality.

## Validation Notes

The Microsoft AppSource and Akvelon blog documentation provide information about the visual's capabilities:

- Supports one date field and multiple measurable columns
- Data is displayed by colored sections within each calendar day based on a percentage of total data available for that day
- Offers in-depth formatting customization options including font styles, calendar colors, and calendar sizes
- Fixed and relative start and end dates options
- Cross selection functionality
- Ability to view data from specific days by selecting them in the calendar
- Customizable first day of the week

## Conclusion

Based on the validation against official documentation, the feature support claims in the matrix for Custom Calendar appear to be accurate. The visual supports basic calendar visualization with customization options as indicated in the matrix. The visual is designed specifically for providing calendar-based data visualization rather than offering advanced filtering functionality.
