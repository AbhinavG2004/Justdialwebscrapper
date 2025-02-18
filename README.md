# Justdial Scraper

## Overview
This Python script scrapes business information from Justdial, extracting details such as names, phone numbers, ratings, review counts, addresses, and locations. The extracted data is saved into both CSV and Excel formats for easy access and further analysis.

## Features
- Extracts business details including name, phone number, ratings, rating count, address, and location.
- Saves scraped data in both CSV and Excel formats.
- Uses BeautifulSoup for parsing HTML.
- Implements exception handling to prevent crashes due to missing elements.

## Prerequisites
Ensure you have Python installed along with the following dependencies:

```bash
pip install beautifulsoup4 openpyxl