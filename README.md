Web Scraping:-

### Overview
Scraped book product details from an e-commerce catalog (`http://books.toscrape.com/`) using Python, `requests`, and `BeautifulSoup`. Cleaned non-standard encoding issues with regular expressions (`re`) and stored structured records into a Pandas DataFrame.

### Extracted Fields
* **Title:** Book name
* **Price_GBP:** Cleaned numerical price in GBP
* **Rating:** Converted star rating string (One–Five) to numerical integers (1–5)
* **Availability:** Stock availability status
* **Product_URL:** Direct detail link

### Output File
* `scraped_books_data.csv` (100 scraped product records across 5 pages)
