# Beyondsoft Calendar Feature Validation Findings

## Overview

Beyondsoft Calendar is a PowerBI custom visual that provides a single-month calendar layout that allows users to better visualize data for each day of the selected month. It supports one date field, one measure field, and any number of tooltip fields. The visual offers many customization features ranging from basic formatting options like font size, color, etc., to more advanced features such as divergent data color scales, data labels, tooltips, and selection interaction.

## Validation Sources

1. [Microsoft AppSource - Beyondsoft Calendar](https://appsource.microsoft.com/en-us/product/power-bi-visuals/wa104381096)
2. [GitHub Repository - BCI Calendar](https://github.com/mannymerino/bci-calendar)
3. [Pragmatic Works Blog - Power BI Custom Visuals - Beyondsoft Calendar](https://pragmaticworks.com/blog/power-bi-custom-visuals-beyondsoft-calendar)

## Feature Support Summary

Based on the original matrix and validation against official documentation:

- Total features: 128
- Features supported (y): 13
- Features not supported (n): 109
- Features with no data (NaN): 6

## Key Features Confirmed

The following key features were explicitly confirmed in the documentation:

1. **Single select** - The visual allows selection of individual days in the calendar
2. **Single/Multi-select** - The visual supports selection interaction functionality
3. **Variance in calendar** - The visual can display data with diverging color scales
4. **Week** - Week numbers can be displayed in the calendar
5. **Week Start Day** - Users can choose the starting day of the week
6. **Year** - The visual can display the year along with the month
7. **Calendar Format** - Extensive calendar formatting options are available
8. **Data Colors** - Support for gradient or fixed color schemes with diverging options
9. **Data Labels** - Customizable data label formatting

## Features Not Supported

According to the matrix, the Beyondsoft Calendar does not support many advanced filtering features that are available in other visuals. This aligns with the documentation which shows Beyondsoft Calendar is focused specifically on calendar visualization rather than filtering capabilities.

Some notable features not supported include:

- Advanced filtering capabilities
- Search functionality
- Slider-based filtering
- Hierarchical data display
- Multiple date range selection

## Validation Notes

The GitHub repository documentation provides detailed information about the visual's capabilities and limitations:

- The visual doesn't support date hierarchies
- The visual will use the month/year from the first date in the selected dataset
- The optimal experience is when the report or page is filtered to view one month at a time
- There is a known issue when using a "Date/Time" (versus "Date") for the Date Field

The Pragmatic Works blog confirms several key features including:
- Visualization of data on a month calendar
- Display of a single measure with tooltip support for additional measures
- Customizable calendar format, data colors, and data labels

## Conclusion

Based on the validation against official documentation, the feature support claims in the matrix for Beyondsoft Calendar appear to be accurate. The visual supports calendar visualization capabilities as indicated in the matrix, with limited support for advanced filtering features. The visual is designed specifically for displaying data in a calendar format rather than providing extensive filtering functionality.
