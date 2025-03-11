# Datepicker by Powerviz Feature Validation Findings

## Overview

Datepicker by Powerviz is an advanced date slicer for PowerBI that allows users to apply page-level filters to date-type columns. It offers multiple display modes, various date selection types, presets, themes, and extensive customization options. The visual is designed to enhance the user experience with a web-like UI design and time-saving features.

## Validation Sources

1. [Powerviz Official Documentation - Date Picker](https://docs.powerviz.ai/powerviz/date-picker/introduction)
2. [Powerviz Blog - 5 Key Features in Date Picker](https://www.powerviz.ai/blog/5-key-features-in-date-picker-by-powerviz-for-power-bi)

## Feature Support Summary

Based on the original matrix and validation against official documentation:

- Total features: 128
- Features supported (y): 38
- Features not supported (n): 83
- Features with no data (NaN): 7

## Key Features Confirmed

The following key features were explicitly confirmed in the documentation:

1. **Display Modes** - Multiple display options including Pop-up and Canvas views
2. **Date Selection Types** - Support for single dates, multiple dates, date ranges, and multiple date ranges
3. **Presets** - Predefined periods and custom presets using DAX measures or calculated columns
4. **Default Selection** - Ability to trigger specific periods automatically upon page reload
5. **Theme Selection** - Professional-looking themes and custom theme creation
6. **Weekend Customization** - Options to choose off days and customize weekend appearance
7. **Holiday Formatting** - Ability to convert custom dates into holidays with markers and color changes
8. **Range/Start-End Selector** - Support for selecting date ranges with start and end dates
9. **Single/Multi-select** - Options for both single date selection and multiple date selection

## Features Not Supported

According to the matrix, Datepicker by Powerviz does not support many advanced filtering features that are not related to date selection, such as complex search capabilities, radio views, and various slider options. This aligns with its purpose as a specialized date slicer rather than a general-purpose filtering tool.

## Validation Notes

The official documentation and blog posts provide detailed information about the visual's capabilities:

- The visual offers four display modes: Pop-up Mode, Canvas Mode, Canvas Mode Display All the Time, and Canvas Mode Hide Out
- It supports four selection types: Date Range Selection, Multiple Dates Selection, Single Date Selection, and Multiple Date Range Selection
- Presets feature allows users to choose predefined periods without manually selecting start and end dates each time
- Default selection feature allows triggering a specific period automatically upon page reload
- The visual offers extensive customization options for weekends, holidays, and invalid dates
- It is a PBI certified visual and part of the Powerviz library suite

## Conclusion

Based on the validation against official documentation, the feature support claims in the matrix for Datepicker by Powerviz appear to be accurate. The visual supports 38 features as indicated in the matrix, with a focus on providing advanced date selection and filtering capabilities. The documentation confirms the presence of key features like multiple display modes, various date selection types, presets, themes, and customization options.
