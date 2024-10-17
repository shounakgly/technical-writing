# New Features and Fixes
A collection of release notes about new features and fixes made to products.
## New Features
|Feature | Description |
|---|---|
|Draw reference lines for time-based category columns | Draw reference lines, format, and control the z-order of reference lines for date and date-time category columns in workbooks. See Add Reference Lines to Visualizations.|
|Provide quick access to content from the navigation menu |Select curated workbook or dashboard folders when saving workbooks or dashboards, enabling a link to that workbook or dashboard to display on the Navigation menu (workbooks) or Dashboards menu (dashboards). See Begin to Build a Workbook and Create Visualizations, and Create Your First Dashboard. |
## Fixes
**Issue CS-373**

An issue occurred where the Online ATP field displayed incorrect values due to the CS Invalid Consolidated Inventory Saved Search no longer including the value of In-Store Reserved Qty in its calculation. The In-Store Reserved Qty field from the Location record, the In-Store Reserved Qty (Product Category), and In-Store Reserved Qty (Item) fields have been added back to the calculation of the CS Invalid Consolidated Inventory Saved Search.

**Action:** Update the In-Store Reserved Qty field in the Location record, In-Store Reserved Qty (Product Category), and the In-Store Reserved Qty (Item) fields with the proper in-store reserved quantities if needed. See the Campus Stores User Guide for more information.

**Testing:** Ensure that the Online ATP field is displaying the correct values. 
