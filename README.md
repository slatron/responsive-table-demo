## Problem Space

I want to display a table with many columns in both desktop and mobile browsers. No table data should be hidden and unavailable to mobile users. I want to use CSS and JS to accomplish this and use the same HTML for desktop and mobile users.

## This Solution

The first cel acts as the "headline" for that row. The initial table will only display that column with a toggle icon to expand that row vertically. When the user expands the row, they will be able to scroll through all row data or collapse the row.

All code is in the single `index.html` file. To see mobile state, resize screen to under 600px. Use toggle icons to view all row data.

This is one simple solution to displaying table data with large column counts on mobile. The entire table is visible at large screen widths. On mobile, only the first row is displayed with a toggle icon. When the user expands the row, they can see all row data vertically with the column name from the data-th attribute used for a label.
