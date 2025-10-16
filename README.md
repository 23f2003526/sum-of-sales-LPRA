# Sales Summary 123123

## Overview
This web application displays a sales summary for various products with their total sales amounts. It includes a currency selector that allows users to view all sales figures converted into the selected currency. The application dynamically updates the sales totals and the active currency display using predefined currency exchange rates.

## Setup
No special setup is required. This is a standalone HTML file that includes Bootstrap via a CDN and uses embedded JavaScript for dynamic functionality.

To use:
1. Save `index.html` locally.
2. Open `index.html` in any modern web browser with JavaScript enabled.

## Usage
- The sales table lists products and their sales totals in the currently selected currency.
- Use the currency dropdown (`#currency-picker`) at the top to select your desired currency.
- The total sales amounts and the footer total automatically convert and update based on the selected currency.
- The currently active currency code is displayed next to the dropdown in `#total-currency`.

## Improvements from Previous Version (Round 2)
- Introduced a fully functional currency selector dropdown (`#currency-picker`) that converts all computed sales totals into the chosen currency using consistent exchange rates.
- Active currency code is mirrored and updated in the `#total-currency` element dynamically as the user changes currency.
- Refactored code for clarity, maintainability, and ensured accessibility usage semantics.
- Added currency formatting for all monetary values using `Intl.NumberFormat` for better localization and consistent appearance.
- Included proper separation of concerns by defining a clear data source and updating UI elements efficiently.

## License
This project is licensed under the MIT License.