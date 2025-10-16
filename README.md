# Sales Summary Web App

## Overview

This is a single-page web application that fetches a CSV file named `data.csv` from the `attachments` subfolder, aggregates sales data by product, and displays both a total sum of all sales as well as a detailed Bootstrap-styled table listing each product with its total sales figure. The total sales value updates to remain accurate after the table is rendered.

The page uses Bootstrap 5 from jsDelivr for styling and provides a responsive, user-friendly interface.

## Setup

1. Place the file `index.html` in a web-accessible folder on your server.
2. Place the CSV file named `data.csv` inside the `attachments` subfolder relative to `index.html`.
   
   - The CSV file **must** contain a header row with at least two columns: `product` and `sales`.
   - Example CSV header: `product,sales,...`

## Usage

Simply open `index.html` in a modern web browser. The page will automatically:

- Fetch `attachments/data.csv`
- Parse and aggregate sales totals by product
- Display a Bootstrap-styled table (`#product-sales`) listing each product with its total sales
- Display the overall total sales amount in the designated summary area (`#total-sales`)
- Keep the overall total accurate and also show it as the table footer total

If the file is missing, improperly formatted, or columns are not present, a relevant message will display instead.

## Improvements from Previous Version (Round 2)

- Added a detailed Bootstrap table (`#product-sales`) showing the sales totals for each product.
- Aggregated sales data by product from the CSV instead of only showing a single total sum.
- Added a footer row in the table to display the combined total sales sum, keeping it accurate and in sync with the main total sales display.
- Improved error handling and clearer messages if required columns (`product` or `sales`) are missing.
- UI enhancements for better readability and responsiveness using Bootstrap table styling.
- Code improvements for clearer logic and separation between aggregating data and rendering the table.

## License

MIT License