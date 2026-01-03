#🕶️ Lenskart Web Scraper – Python Automation Project

A complete web scraping automation project built using Python, Selenium, and BeautifulSoup to extract product data from Lenskart across multiple categories with dynamic scrolling, image downloading, and CSV consolidation.

📌 Project Overview

This project automates the extraction of product information from Lenskart’s website, handling:

Dynamic infinite scrolling

Multiple category pages

Automatic product count detection

Image downloading

Structured CSV storage

Merging multiple category files into one dataset

The final output is a clean, analytics-ready CSV file containing all scraped products with category tagging.

🚀 Features

✅ Scrapes multiple Lenskart categories

🔄 Handles infinite scroll automatically

📦 Extracts:

Brand Name

Price

Original Price

Discount

Rating

Number of Reviews

Product Link

Image URL

🖼️ Downloads product images safely

📂 Saves category-wise CSV files

🔗 Merges all CSVs into one master dataset

🏷️ Adds a clean Category column

🧹 Removes duplicates automatically

🛠️ Tech Stack

Python 3.10+

Selenium

BeautifulSoup (bs4)

Pandas

Requests

ChromeDriver

📁 Project Structure
Lenskart-Web-Scraper/
│
├── scraper/
│   ├── lenskart_scraper.py        # Main scraping script
│   ├── merge_csv.py               # Merge all CSV files
│
├── output/
│   ├── lenskart_eyeglasses.csv
│   ├── lenskart_sunglasses.csv
│   ├── lenskart_kids_eyeglasses.csv
│
├── images/
│   ├── Eyeglasses/
│   ├── Sunglasses/
│
├── final_products.csv             # Final merged dataset
│
├── requirements.txt
├── README.md
└── .gitignore

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/Lenskart-Web-Scraper.git
cd Lenskart-Web-Scraper

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Install ChromeDriver

Make sure Google Chrome is installed

ChromeDriver will be handled automatically using webdriver-manager

▶️ How to Run
🔹 Run the Scraper
python scraper/lenskart_scraper.py


This will:

Open each category page

Scroll dynamically

Extract all products

Save category-wise CSV files

Download product images

🔹 Merge All CSV Files
python scraper/merge_csv.py


This will:

Merge all category CSV files

Add a clean Category column

Save final_products.csv

📊 Sample Output (final_products.csv)
Brand	Price	Original Price	Discount	Rating	Reviews	Category
Vincent Chase	₹999	₹1999	50% OFF	4.5	1,245	Eyeglasses
Lenskart Air	₹1499	₹2499	40% OFF	4.7	890	Computer Glasses
⚠️ Important Notes

This project is built for educational and learning purposes

Avoid aggressive scraping

Respect website robots.txt and Terms of Service

Use reasonable delays to prevent IP blocking

📌 Learning Outcomes

Real-world web scraping

Handling dynamic content with Selenium

Infinite scrolling logic

Data cleaning and structuring

CSV automation

File and folder management

Production-ready scraping workflow

🔮 Future Enhancements

🧠 Convert to Scrapy framework

🌐 Add proxy & user-agent rotation

📦 Store data in SQL / MongoDB

📊 Build a Streamlit dashboard

⏱️ Schedule scraping using cron jobs

☁️ Deploy on cloud (AWS / GCP)

👨‍💻 Author

Aashu Sharma
Aspiring Financial & Data Analyst
Python | Data Analytics | Web Automation

📎 LinkedIn: (Add your profile link)
📁 GitHub: (This repository)
