# Preselected Slicer - Feature Validation

## Overview
The Preselected Slicer is a custom visual for Power BI developed by Insiders.coop. It functions as a standard slicer but with the added capability of having values pre-selected by data in your model.

## Official Documentation Sources
1. [INSIDERS.COOP Documentation](https://insiders-coop.github.io/pbiviz-docs/preselected-slicer)
2. [Microsoft AppSource](https://appsource.microsoft.com/en-us/product/power-bi-visuals/insiderscoop1611244107840.powerbi_customviz_preselected-slicer)
3. [Owen Auger's BI Blog - Exploring slicer default selections](https://owenaugerbi.com/exploring-slicer-default-selections/)

## Key Features Verified

### Dynamic Default Selection
- **Feature Support**: ✅ Yes
- **Description**: The primary feature of this visual is the ability to use another column or measure to determine which values should be pre-selected when a user opens the report. This allows for dynamic default selections that can change based on data (e.g., always showing the current month).
- **Implementation**: Requires a "Pre Selection" field that determines which values should be selected by default.

### Appearance Customization
- **Feature Support**: ✅ Yes
- **Description**: The visual supports appearance customization as indicated in the feature matrix.

### Checklist View
- **Feature Support**: ✅ Yes
- **Description**: The visual supports a checklist view for selection options.

### Hide Blanks
- **Feature Support**: ✅ Yes
- **Description**: The visual allows hiding blank values in the slicer.

### List View
- **Feature Support**: ✅ Yes
- **Description**: The visual supports displaying items in a list view format.

### Radio View
- **Feature Support**: ✅ Yes
- **Description**: The visual supports displaying items in a radio button format for single selection.

### Search with Suggestion
- **Feature Support**: ✅ Yes
- **Description**: The visual includes search functionality with suggestions.

### Show Blank as/Add Value in Empty String
- **Feature Support**: ✅ Yes
- **Description**: The visual allows customization of how blank values are displayed.

### Single/Multi-select
- **Feature Support**: ✅ Yes
- **Description**: The visual supports both single and multiple selection modes.

### Sync Slicer
- **Feature Support**: ✅ Yes
- **Description**: The visual supports synchronization with other slicers.

### Zoom
- **Feature Support**: ✅ Yes
- **Description**: The visual supports zoom functionality.

## Technical Requirements

The Preselected Slicer requires three components for proper configuration:
1. The dimension to slice on in the "Fields" bucket
2. A column giving the pre-selections in the "Pre Selection" bucket
3. A "technical" measure in the "Dirty Status" bucket that must be unique for each slicer instance

## Known Issues

There is a documented issue with the slicer's dropdown list which doesn't flow over other visuals. This is due to the technical limitation that custom visuals are HTML documents embedded in iframes, which constrains elements within the bounds of the containing iframe.

## Certification Status
The visual is Microsoft PBI Certified as indicated on the AppSource page.

## Conclusion
The Preselected Slicer effectively delivers on its primary value proposition of allowing dynamic default selections based on data values. The feature claims in the matrix are accurate based on the documentation reviewed.
