# Real-time-Stock-Price-Scrapping-and-Analysis
## Overview

This project demonstrates how to scrape real-time stock price data from websites and save it for further analysis. Utilizing Python’s BeautifulSoup, Requests, and Pandas libraries, the script extracts essential stock details such as company name, current price, price change from specified URLs. The data is then structured into a DataFrame and exported as an Excel file for analysis.

## Features

Web Scraping: Fetch real-time stock prices, price changes.

Error Handling: Implements try-except blocks to handle missing elements during scraping.

Data Storage: Saves scraped data into a structured Excel file.

Custom User-Agent: Prevents being flagged as spam during scraping by using headers.

## Technologies Used

Python Libraries:

BeautifulSoup: For parsing HTML and extracting data from web pages.

Requests: For making HTTP requests to target URLs.

Pandas: For data manipulation and exporting to Excel.

## How It Works

Define Target URLs: A list of URLs pointing to stock pages on Groww.

Scrape Stock Data: Extract relevant details using class IDs or tags from the HTML structure.

Error Handling: Manage missing elements or changes in webpage structure gracefully.

Export to Excel: Store the collected data in an Excel file for further analysis.
