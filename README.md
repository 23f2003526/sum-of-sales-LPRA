# Sales Summary 123123

## Overview  
This web application displays a sales summary for various products with their total sales amounts. It features a currency selector to convert all sales figures into the chosen currency dynamically, and now also includes a region filter allowing users to view sales by specific regions or all regions combined. The total sales values update accordingly based on both the selected currency and region filter.

## Setup  
No special setup is required. This is a standalone HTML file that includes Bootstrap via CDN and uses embedded JavaScript for dynamic functionality.

To use:  
1. Save `index.html` locally.  
2. Open `index.html` in any modern web browser with JavaScript enabled.

## Usage  
- The sales table lists products and their sales totals in the currently selected currency and filtered by the selected region.  
- Use the "Currency" dropdown (`#currency-picker`) at the top to pick your desired currency. All sales amounts convert accordingly.  
- Use the "Region" dropdown (`#region-filter`) to filter the sales shown by region or select "All" to see all regions combined.  
- The total sales amount and the footer total update dynamically to reflect both the selected currency and region.  
- The currently active currency code is displayed next to the currency selector in `#total-currency`.  
- The large total at the top indicates the sales total for the currently selected region and is updated live. It also holds the active region in its `data-region` attribute.

## Improvements from Previous Version (Round 2)  
- Added a **region filter** dropdown (`#region-filter`) enabling users to filter sales by region (North America, Europe, Asia, Australia, or All).  
- The total sales displayed in `#total-sales` update to show the sum of filtered sales and have their `data-region` attribute set to the active region value.  
- The total sales alert text updates to visually indicate the currently selected region.  
- Ensured currency formatting consistency across filtered results and total displays.  
- Improved layout and labeling for combined currency and region selectors for better usability and accessibility.  
- Maintained previous features such as currency conversion with consistent exchange rates and currency formatting using `Intl.NumberFormat`.  
- Code modularized for clarity and easy maintainability.

## License  
This project is licensed under the MIT License.