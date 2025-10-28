# python-selenium-web-scraper

Python and Selenium project that scrapes book data from a website and saves it to Excel. Demonstrates web automation and data extraction skills.

This project uses Python and Selenium to scrape book data from a website and save it to an Excel file. It demonstrates web automation and data extraction skills.

## Technologies
- Python 3.10
- Selenium
- Firefox
- Pandas
- openpyxl

## Setup
1. Firefox and geckodriver.exe must be installed.
2. Install required Python packages:
```bash
pip install selenium pandas openpyxl

    Update the Firefox and geckodriver paths in the script according to your system.

Usage

python scraper.py

Output

    Excel file: books_raporu.xlsx

    Contains book title, price, and link.

Note: Only the first page of books is scraped. Looping can be added to scrape additional pages.
