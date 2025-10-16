# Sales Summary Web App

## Overview

This single-page site fetches a CSV file named `data.csv` from the `attachments` folder, sums the values from its `sales` column, and displays the total on the page in an element with the ID `total-sales`. The page’s title is set to `Sales Summary 123123` and the layout uses Bootstrap 5 loaded via jsDelivr CDN.

## Setup

1. Place `index.html` in your web server root or any accessible folder.
2. Place the CSV file named `data.csv` inside the `attachments` subfolder relative to `index.html`.

## Usage

Open `index.html` in a compatible web browser. The page will automatically fetch the CSV file, sum the sales values, and display the total. If the CSV file cannot be loaded or parsed properly, an error message or notice will appear instead.

## License

MIT License