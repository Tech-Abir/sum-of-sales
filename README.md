# Overview
This is a minimal single-page web app that:
- Loads Bootstrap 5 from jsdelivr.
- Fetches the attached data.csv file.
- Sums its "sales" column.
- Sets the document title to "Sales Summary {seed}" (seed is expected to be provided by the environment).
- Displays the computed total inside the element with id="total-sales".

# Setup
No build tools are required.

Steps:
1. Ensure data.csv is in the same directory as index.html.
2. Open index.html in a modern web browser.

# Usage
- On load, the page will fetch data.csv, compute the sum of the "sales" column, and display it.
- The document title will be set to "Sales Summary {seed}" if a global variable named seed is available in the environment. If not, it will show "Sales Summary " with an empty suffix.