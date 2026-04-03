# Books to Scrape — Web Crawling Project

##  Overview

This project demonstrates web scraping using Python with the BeautifulSoup library.  
The goal is to extract structured data from the website **Books to Scrape** and perform basic data processing.

The project focuses on collecting book information across multiple categories and identifying the most expensive books.

---

##  Objectives

- Scrape book data from 10 categories
- Extract information for 10 books in each category
- Collect the following attributes:
  - Category
  - Title
  - Price
- Store the data in a structured format (DataFrame)
- Convert price values into numeric format
- Identify the top 10 most expensive books

---

##  Data Source

- Website: http://books.toscrape.com/

---

##  Technologies Used

- Python
- requests
- BeautifulSoup (bs4)
- pandas

---

##  Project Structure

```bash
.
├── script.py              # main scraping script
├── books_dataset.bin      # saved dataset (binary format)
└── README.md
```
## How It Works

1. Get Categories
Extract category links from the main page
2. Scrape Books
Visit each category
Collect:
Title (from title attribute)
Price
3. Data Processing
Convert prices from string to numeric format
Store all data in a DataFrame
4. Analysis
Sort books by price
Extract top 10 most expensive books
