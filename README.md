# Project Title: Jumia Web Scrapper and Price Tracker

# Introduction:
  The Jumia Shirt Scrapper and Price Tracker project aims to scrape product information from the Jumia Nigeria website and track the prices of men's shirts over time. The project utilizes web scraping techniques to extract relevant data from the website and stores it in a CSV file. Additionally, it includes a price tracking feature that periodically checks for updates in the product's price and appends the new data to the CSV file. The project demonstrates proficiency in web scraping, data storage, and basic price tracking functionality.

# Objectives:
- Web Scraping: Extract product information, including the name, price, and old price, from the Jumia Nigeria website using the BeautifulSoup library.

- Data Storage: Create a CSV file named "jumia_scrap_project.csv" to store the scraped data. The CSV file includes headers for the name_of_item, price, and old_price columns.

- Initial Data Extraction: Scrape the product information for men's shirts from a specific page of the Jumia website (e.g., page 4) and write the data to the CSV file.

- Iterative Price Tracking: Implement a function called "check_price" that retrieves the latest price information for a specific product page and appends the data to the CSV file. The function should be set to run periodically (e.g., every 5 seconds) to track any price changes over time.

- Data Analysis: Load the CSV file into a pandas DataFrame for further analysis and manipulation. Perform basic data operations, such as filtering and sorting, to gain insights from the collected data.

# Project Workflow:
# Import the necessary libraries: BeautifulSoup, requests, csv, time, datetime, and pandas.

- Scrape the product information from the Jumia Nigeria website by sending an HTTP request to the desired URL using the requests library.

- Parse the HTML content using BeautifulSoup and locate the relevant sections and elements to extract the name, price, and old price of the shirts.

- Open a CSV file named "jumia_scrap_project.csv" in write mode and create a csv.writer object. Write the headers (name_of_item, price, old_price) to the CSV file.

- Iterate over the scraped articles and extract the name, price, and old price values. Handle any exceptions for missing old prices.

- Write the extracted data (name_of_item, price, old_price) to the CSV file using the csv.writer object.

- Implement a function named "check_price" that retrieves the latest price information for a specific product page, appends the data to the CSV file, and sets a delay between checks (e.g., 5 seconds).

- Load the CSV file into a pandas DataFrame for further data analysis and manipulation.

# Conclusion:
The Jumia Web Scrapper and Price Tracker project demonstrates your ability to extract data from websites using web scraping techniques, store the data in a CSV file, and track price changes over time. This automate data collection and tracking processes and provides valuable insights into the pricing dynamics of men's shirts on the Jumia Nigeria website.

