🕶️ Lenskart Web Scraper – Python Automation Project

A complete end-to-end web scraping project built using Python, Selenium, and BeautifulSoup to extract product data from Lenskart across multiple categories.
The project handles dynamic infinite scrolling, automatic product count detection, image downloading, and CSV consolidation into a single master dataset.

This project is designed to demonstrate real-world scraping logic, data handling, and automation skills and is suitable for portfolio and GitHub showcase purposes.

📌 Project Highlights

Scrapes multiple Lenskart category pages

Automatically detects total product count

Handles infinite scroll pages

Extracts structured product data

Downloads product images safely

Saves category-wise CSV files

Merges all CSVs into one final dataset

Adds a clean, non-repeating category column

Built with scalable and reusable code

📦 Data Extracted

For each product, the following information is collected:

Brand Name

Offer Price

Original Price

Discount

Rating

Number of Reviews

Product Page URL

Image URL

Category Name

🛠️ Tech Stack

Python 3

Selenium WebDriver

BeautifulSoup (bs4)

Pandas

Requests

webdriver-manager

Google Chrome

📁 Project Structure
Lenskart-Web-Scraper/
│
├── scraper/
│   ├── lenskart_scraper.py        # Main scraping script
│   ├── merge_csv.py               # Merge all category CSV files
│
├── output/
│   ├── lenskart_all-computer-glasses.csv
│   ├── lenskart_all-kids-eyeglasses.csv
│   ├── lenskart_bestsellers-premium-eyeglasses.csv
│   ├── lenskart_eyeglasses.csv
│   ├── lenskart_sunglasses.csv
│
├── images/
│   ├── all-computer-glasses/
│   ├── all-kids-eyeglasses/
│   ├── bestsellers-premium-eyeglasses/
│
├── final_products.csv             # Final merged dataset
│
├── requirements.txt
├── README.md
└── .gitignore

⚙️ Setup & Installation
1️⃣ Clone the Repository
git clone https://github.com/aashu-sharma/Lenskart-Web-Scraper.git
cd Lenskart-Web-Scraper

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Chrome & WebDriver

Ensure Google Chrome is installed

ChromeDriver is handled automatically via webdriver-manager

▶️ How to Run the Project
🔹 Step 1: Run the Scraper
python scraper/lenskart_scraper.py


This will:

Open each Lenskart category page

Detect total product count

Perform smart scrolling

Extract all product data

Download images

Save category-wise CSV files

🔹 Step 2: Merge All CSV Files
python scraper/merge_csv.py


This will:

Merge all category CSVs

Add a unique category name per product

Remove duplicates

Generate final_products.csv

📊 Sample Output (final_products.csv)
Brand	Price	Original Price	Discount	Rating	Reviews	Category
Vincent Chase	₹999	₹1999	50% OFF	4.5	1245	Computer Glasses
Lenskart Air	₹1499	₹2499	40% OFF	4.7	890	Eyeglasses
John Jacobs	₹1999	₹3499	43% OFF	4.6	560	Kids Eyeglasses
🧠 Key Concepts Demonstrated

Dynamic content scraping

Infinite scroll handling

DOM inspection and parsing

Automation using Selenium

Error-safe image downloading

Data cleaning and merging

Scalable scraper design

⚠️ Disclaimer

This project is created strictly for educational and learning purposes.
Please respect the website’s Terms of Service and avoid excessive requests while scraping.

🚀 Future Enhancements

Scrape detailed product specification pages

Store data in SQL / NoSQL database

Add logging instead of print statements

Headless browser support

Proxy & user-agent rotation

Build a dashboard using Streamlit

👨‍💻 Author

Aashu Sharma
Aspiring Financial & Data Analyst
Python | Data Analytics | Web Automation

⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.
