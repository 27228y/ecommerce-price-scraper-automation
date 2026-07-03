# E-Commerce Catalog & Price Scraper

A modular Python script that scrapes paginated e-commerce sites, extracts product and pricing data, cleans the raw text, and generates formatted Excel reports with conditional formatting.

## Why This Matters
Manual competitor price tracking is slow and prone to human error. This script automates the entire pipeline, turning multi-page archives into clean, structured spreadsheets in seconds.

## Tech Stack
* **Python 3**
* **BeautifulSoup4 & Requests:** Handles HTTP requests and HTML parsing.
* **Pandas:** Manages data structuring and data cleaning.
* **OpenPyXL Engine:** Handles Excel generation, auto-adjusts column widths, and applies conditional formatting.

## Key Features
* **Built-in Rate Limiting:** Includes explicit delays (time.sleep) to respect target servers and avoid IP blocks.
* **Data Sanitization:** Strips currency symbols and white spaces, converting raw text prices into clean numeric types (float).
* **Auto-Fit Excel Columns:** Automatically adjusts column widths based on the longest string to prevent clipped data.
* **Visual Price Alerts:** Highlights items priced under a specific threshold (e.g., £20.00) using OpenPyXL conditional formatting.
