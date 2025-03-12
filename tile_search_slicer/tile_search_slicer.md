# Tile Search Slicer - Feature Validation

## Overview
The Tile Search Slicer by TME AG is a custom visual for Power BI that provides searching and filtering data to enable data selections via tiles with extensive customization options for each component.

## Official Documentation Sources
1. [TME AG Official Website](https://tme-ag.de/tile-search-slicer/)
2. [Microsoft AppSource](https://appsource.microsoft.com/en-au/product/power-bi-visuals/WA200001580)

## Key Features Verified

### Appearance Customization
- **Feature Support**: ✅ Yes
- **Description**: The visual is highly customizable with options for font-family, text-size, alignment, border-color, border-radius, and hover color. Users can customize the background color, text color, and padding of each tile inside the panel.

### Observer Mode
- **Feature Support**: ✅ Yes
- **Description**: The visual provides two panels - one with selected items and another with unselected items, allowing users to observe the current filter state.

### Search with Suggestion
- **Feature Support**: ✅ Yes
- **Description**: The visual supports searching single or multiple items in the data, with a search input field that is also customizable.

### Single/Multi-select
- **Feature Support**: ✅ Yes
- **Description**: Users can select single or multiple tiles, with the option to set a restriction on the maximum number of tiles that can be selected.

### Sync Slicer
- **Feature Support**: ✅ Yes
- **Description**: The visual explicitly supports the Sync slicer feature, allowing it to be synchronized with other slicers in the report.

## Additional Features (Not in Matrix)
- **Maximum Data Access**: Uses Power BI's 'fetchMoreData' API to get the maximum number of records available beyond the standard 30,000 record limit
- **Selection Management**: Users can restrict the number of selected tiles shown (default is 4) and manage the height of the selected panel
- **Filter and Select All Buttons**: Provides buttons to clear all selections or select all tiles at once
- **Customizable Columns**: Users can set the number of columns for each selected and unselected panel
- **Bookmark Support**: Supports Power BI bookmarks functionality
- **High Contrast Mode**: Supports high contrast mode for accessibility

## Certification Status
The visual is available on Microsoft AppSource with a rating of 4.2 (9 ratings).

## Conclusion
The Tile Search Slicer by TME AG delivers on its promise of providing extensive customization options for data selection via tiles. The feature claims in the matrix are accurate based on the documentation reviewed, with the visual supporting appearance customization, observer mode, search functionality, single/multi-select capability, and sync slicer functionality.
