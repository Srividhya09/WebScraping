# WebScraping
# Amazon Product Scraper

This project involves scraping product information from Amazon. The script collects data such as product titles, prices, ratings, review counts, and availability status.

## Features

- Extracts product titles, prices, ratings, review counts, and availability status
- Handles missing data gracefully
- Stores the scraped data in a CSV file

## Requirements

- Python 3.12
- BeautifulSoup
- Requests
- Pandas
- NumPy

## Installation

1. Clone the repository:
    git clone https://github.com/Srividhya09/WebScraping.git


2. Navigate to the project directory:
    cd WebScraping


3. Ensure you have all the required libraries installed. You can install them using pip:
    pip install beautifulsoup4 requests pandas numpy

4. Update the `HEADERS` dictionary with your user agent string. You can find your user agent string by searching "my user agent" on the web and copying the resulting string.

5. Run the scraping script:
    python Sales_Analysis.py

## Usage

- The script `amazon_scraper.py` performs the following tasks:
  - Sends an HTTP request to the Amazon search results page for "playstation 4".
  - Extracts links to individual product pages from the search results.
  - Scrapes product details (title, price, rating, reviews, availability) from each product page.
  - Stores the scraped data in a DataFrame and saves it to `amazon_data.csv`.

## Data Scraping Steps

1. Importing Libraries
   - The necessary libraries for web scraping and data manipulation are imported.

2. Defining Functions
   - Functions are defined to extract product details such as title, price, rating, review count, and availability status.

3. Sending HTTP Request
   - An HTTP request is sent to the Amazon search results page for "playstation 4".

4. Parsing HTML Content
   - BeautifulSoup is used to parse the HTML content of the search results page.

5. Extracting Product Links
   - Links to individual product pages are extracted from the search results.

6. Scraping Product Details
   - For each product link, an HTTP request is sent, and the HTML content is parsed to extract product details using the defined functions.

7. Storing Data
   - The scraped data is stored in a DataFrame and saved to `amazon_data.csv`.

## Screenshot

![Screenshot (196)](https://github.com/Srividhya09/WebScraping/assets/170795002/204902b6-15cc-462f-9e8f-e9d736d664de)
