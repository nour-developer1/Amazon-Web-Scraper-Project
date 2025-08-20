# Amazon Web Scraper Project

## Overview

This project is a Python-based Amazon Web Scraper implemented in a Jupyter Notebook. It extracts product details from Amazon product listings, processes the data, and stores the results for analysis. The scraper leverages `BeautifulSoup` for parsing HTML and `requests` for making HTTP requests.

## Features

* Scrapes product details such as:

  * Product Title
  * Price
  * Rating
  * Number of Reviews
  * Availability
* Data cleaning and transformation for structured storage.
* Export functionality to CSV for further analysis.
* Supports automation and scheduling for continuous scraping.

## Project Structure

* **Amazon Web Scraper Project.ipynb**: Main notebook containing the scraping logic, data extraction, and export pipeline.
* **Output CSV file(s)**: Saved data for analytics and reporting.

## Requirements

Install the required dependencies:

```bash
pip install requests beautifulsoup4 pandas
```

## Usage

1. Open the notebook `Amazon Web Scraper Project.ipynb`.
2. Update the target Amazon product URL(s) in the designated cell.
3. Run the cells sequentially to:

   * Fetch HTML content
   * Parse product details
   * Clean and structure the data
   * Save the output to CSV

## Limitations

* Amazon applies anti-scraping measures such as CAPTCHAs and dynamic content loading, which may restrict scraping.
* Frequent scraping from the same IP may result in blocking.
* This scraper is designed for educational and research purposes only.

## Possible Enhancements

* Integrate with Selenium or Playwright for dynamic content handling.
* Add proxy and user-agent rotation to minimize blocking.
* Extend functionality to track price changes over time.
* Automate scheduling with tools like Airflow or Cron.

## Disclaimer

This project is intended for **educational purposes only**. Scraping Amazon or other e-commerce websites may violate their Terms of Service. Always check the legality and ethical implications before deploying web scrapers in production.
