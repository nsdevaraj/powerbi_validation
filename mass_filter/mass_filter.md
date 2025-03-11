# Mass Filter

## Documentation Sources
1. [Insiders.coop Documentation](https://insiders-coop.github.io/pbiviz-docs/mass-filter)
2. [Medium Article](https://medium.com/power-bi-use-cases/power-bi-mass-filter-visual-ccbbc869c2cb)

## Description
Mass Filter is a Power BI custom visual that allows users to filter reports instantly with a list of keywords through copy/paste functionality. It enables users to copy a list of keywords from any external source (Excel, CSV, plain text file) and paste it in the input box to filter the report on multiple values at once.

## Key Features
- Bulk filtering through copy/paste functionality
- Support for both inclusive and exclusive filtering modes
- Keywords can be separated by commas or line breaks
- Support for quoted text when data contains commas or spaces
- No limit to the number of keywords that can be pasted
- Automatic removal of duplicates in the list
- Simple configuration with dimension selection in Fields bucket
- PBI Certified visual

## Feature Verification (Based on Matrix)
According to the feature matrix in the repository:

| Feature | Support (Y/N) |
|---------|---------------|
| Bulk Paste | y |
| Delimiter | y |
| Enclude/Include the selected value | y |
| Operator - (AND/OR) | n |
| Search with regen/wildcard/operator | y |
| Single/Multi-select | n |
| Sync Slicer | y |

## Additional Notes
- The visual is developed by Insiders.coop
- It's available for free on Microsoft AppSource
- The visual is certified by Power BI
- Particularly useful for filtering reports with many categories that would be time-consuming to select individually
- Provides a significant efficiency improvement over manual selection in the filter pane
