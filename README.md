# Web Scraping with Selenium

This project demonstrates how to scrape data from a website using Selenium. The website contains a table with pagination, and one of the columns in the table contains PDF links.

## Overview

The script uses Selenium to automate the process of navigating through the website, extracting the table data, and downloading the PDF files. It handles pagination to ensure that all data is captured.

## Usage

1. **Requirements:**
   - Python 3.x
   - Selenium
   - WebDriver for your browser (e.g., ChromeDriver)

2. **Installation:**
   - Clone the repository.
   - Install the required dependencies using `pip install -r requirements.txt`.
   - Download the WebDriver for your browser and place it in the project directory.

3. **Execution:**
   - Run the script `Web Scrapig.ipynb`.
   - Follow the on-screen instructions to provide the URL of the website, specify the number of pages to scrape, and choose the directory to save the PDF files.

4. **Output:**
   - The script will scrape the table data, including the PDF links, and save the PDF files to the specified directory.


## Acknowledgements

- Selenium
