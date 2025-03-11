# Hierarchy Slicer

## Documentation Sources
1. [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi-visuals/wa104380820?tab=overview)
2. [Pragmatic Works Blog](https://pragmaticworks.com/blog/power-bi-custom-visuals-hierarchy-slicer)

## Description
The Hierarchy Slicer is a Power BI custom visual that allows users to create a hierarchy of different fields and use it as a slicer to filter other report items. Each level can be expanded or collapsed for optimal navigation through the hierarchy to find and select (multi or single) the correct attribute from the slicer.

## Key Features
- Create hierarchies using single fields or pre-defined hierarchies
- Expand and collapse each level for optimal navigation
- Support for both single and multi-select options
- Display measure values at the lowest level
- Extra search options
- Support for report page tooltips
- Ctrl selection option
- Only leaf selection option
- Support for ragged hierarchies
- Support for ISFILTERED() DAX function
- Support for high contrast modes
- Header restatement functionality
- Header outline support

## Feature Verification (Based on Matrix)
According to the feature matrix in the repository:

| Feature | Support (Y/N) |
|---------|---------------|
| Appearance | y |
| Bookmark support | y |
| Calculated column using DAX - UI | y |
| Hide Blanks | y |
| Hierarchy - Aggregations at parent level | n |
| Hierarchy Mode (Tree view) | y |
| Leaf Only (on selection on parent) | y |
| List view | n |
| Search (with suggestion) | y |
| Single/Multi-select | y |
| Sync Slicer | y |
| Toggle View Type | y |
| UI - Expand All/ Collapse All | y |
| Values (Numbers/Measures) Display | y |
| Zoom | y |

## Additional Notes
- The visual is developed by DataScenarios
- It's available for free on Microsoft AppSource
- The visual is certified by Power BI
- Total visible items are limited to approximately 30,000 items for optimal performance
- There is no limit to the number of levels
- Hierarchies with levels that use multiple columns as key are not supported and can generate incorrect selections
- The visual has been rewritten to version API 2.5 with extra options for ragged hierarchies
