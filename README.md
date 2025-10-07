# Sales Summary Test

## Summary
This static web application fetches a CSV file, calculates the total sales from the data, and displays the result on a single-page site titled 'Sales Summary Test'. It utilizes Bootstrap 5 for styling and is designed to provide a simple sales summary report. New features include the addition of a Bootstrap table (#product-sales) listing each product with its sales.

## Setup
To deploy this application on GitHub Pages, follow these steps:
1. Create a new repository on GitHub.
2. Upload your HTML, CSS, JavaScript files to the repository.
3. Go to the repository's settings and scroll down to the GitHub Pages section.
4. Choose the main branch as the source and save the settings.
5. Access the deployed site at https://your-username.github.io/your-repository-name.

## Usage
- Access the page by visiting the deployed site on GitHub Pages.
- Key Features:
  - Fetches data from `data.csv`.
  - Sums the sales column from the CSV data.
  - Displays the total sales in the element with ID `#total-sales`.
  - Includes a Bootstrap table (#product-sales) listing each product with its sales.

## Code Explanation
This web application is built using HTML, JavaScript, and Bootstrap 5 from jsdelivr for styling. The key parts of the implementation include:
- Fetching and parsing the CSV file to extract sales data.
- Calculating the total sales by summing up the values from the sales column.
- Setting the title of the page to 'Sales Summary Test'.
- Displaying the total sales in the designated HTML element.
- Adding a Bootstrap table (#product-sales) to list each product with its sales.

**Libraries Used:**
- Bootstrap 5 from jsdelivr (for CSS styling)

## License
This project is licensed under the MIT License.