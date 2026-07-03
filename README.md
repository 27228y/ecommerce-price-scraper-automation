# E-Commerce Catalog & Price Scraper

I built a Python script to automate extracting product data from an e-commerce catalog across multiple pages. Instead of clicking and copying data manually, the script visits each page, grabs the book titles and prices, and cleans up the text automatically.

How it works:
- Uses Requests and BeautifulSoup to read the website's HTML code.
- Automatically handles pagination to scrape all pages in one run.
- Cleans text strings into numbers so they can be sorted.
- Saves everything into Excel sheet using Pandas and OpenPyXL.
- Automatically resizes columns and highlights books under £20 green
