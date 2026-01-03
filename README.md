Lenskart-Web-Scraper – Dynamic Product Data Extraction

aashusharma08/Lenskart-Web-Scraper


📌 Project Overview

This project is a Python-based web scraping application that extracts product data from Lenskart’s dynamic e-commerce website.
It uses Selenium to handle infinite scrolling and BeautifulSoup to parse HTML content, enabling structured extraction of product information across multiple categories.

The objective is to demonstrate real-world web scraping of JavaScript-heavy websites, automated data collection, and dataset consolidation.


📂 Features

Scrapes multiple Lenskart category pages

Dynamically detects total product count per page

Handles infinite scrolling efficiently

Extracts structured product-level data

Downloads product images safely

Saves category-wise CSV files

Merges all category data into a single CSV

Adds a clean and unique category column


🛠️ Technologies Used

Python – Core programming language

Selenium – Browser automation and dynamic content handling

BeautifulSoup (bs4) – HTML parsing

pandas – Data manipulation and CSV merging

requests – Image downloading

webdriver-manager – Automatic ChromeDriver management


📥 Installation

Ensure Python is installed (Python 3.10+ recommended).
Install the required libraries:

pip install selenium beautifulsoup4 pandas requests webdriver-manager


📌 Usage
Step 1: Run the Web Scraper
python lenskart_scraper.py


This script:

Opens each Lenskart category page

Detects the total number of products

Performs smart scrolling

Extracts product details

Downloads images

Saves category-wise CSV files

Step 2: Merge All CSV Files
python merge_csv.py


This creates a single consolidated dataset (final_products.csv) with an additional Category column.


📊 Data Extracted

Each product record includes:

Brand Name

Offer Price

Original Price

Discount

Rating

Number of Reviews

Product URL

Image URL

Category Name


📌 Learning Outcomes

Scraping JavaScript-rendered websites

Handling infinite scroll logic

Working with dynamic DOM elements

Data cleaning and consolidation

Building scalable scraping pipelines


📌 Contribution

Contributions are welcome.
Fork the repository, make improvements, and submit a pull request.


📜 License

This project is open-source and available under the MIT License.


📧 Contact

For queries or collaboration, reach out via GitHub
or email: aaashu51767@gmail.com
