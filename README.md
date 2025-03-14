# 🛒 E-Commerce Web Scraper

## 🚀 Project Overview
This project is a **web scraper** designed to extract product details from multiple e-commerce websites using **Selenium and BeautifulSoup**. The scraper fetches product names, prices, ratings, and supplier details, storing them in **CSV, Excel, and an SQLite database**.

## 📌 Features
- ✅ Scrapes product details from **Amazon, eBay, Jumia, Alibaba, Best Buy, and Walmart**.
- ✅ Uses **Selenium** to handle JavaScript-based loading and anti-bot protection.
- ✅ Saves data in **CSV, Excel, and SQLite database**.
- ✅ Implements **randomized delays** to mimic human browsing behavior.

## 📂 Project Structure
```
Ecommerce_Scraper/
│── data/                 # Folder for storing extracted data (CSV, Excel, SQLite)
│── scripts/
│   ├── amazon_scraper.py  # Amazon scraping script
│   ├── ebay_scraper.py     # eBay scraping script
│   ├── jumia_scraper.py    # Jumia scraping script
│   ├── alibaba_scraper.py  # Alibaba scraping script
│   ├── bestbuy_scraper.py  # Best Buy scraping script
│   ├── walmart_scraper.py  # Walmart scraping script
│── venv/                 # Virtual environment (optional)
│── requirements.txt       # Dependencies for the project
│── README.md              # Project documentation
```

## 🔧 Installation & Setup

### 1️⃣ **Clone the Repository**
```bash
git clone https://github.com/yourusername/ecommerce_scraper.git
cd ecommerce_scraper
```

### 2️⃣ **Set Up Virtual Environment (Optional)**
```bash
python -m venv venv  # Create virtual environment
source venv/bin/activate  # Mac/Linux
venv\Scripts\activate  # Windows
```

### 3️⃣ **Install Dependencies**
```bash
pip install -r requirements.txt
```

### 4️⃣ **Run a Scraper**
To scrape products from a specific website, run the corresponding script:
```bash
python scripts/amazon_scraper.py  # Scrape Amazon
python scripts/ebay_scraper.py    # Scrape eBay
python scripts/jumia_scraper.py   # Scrape Jumia
python scripts/alibaba_scraper.py # Scrape Alibaba
python scripts/bestbuy_scraper.py # Scrape Best Buy
python scripts/walmart_scraper.py # Scrape Walmart
```

## 📊 Output
Each script generates the following files inside the `data/` folder:
- `amazon_products.csv`, `ebay_products.csv`, `jumia_products.csv`, etc.
- `amazon_products.xlsx`, `ebay_products.xlsx`, `jumia_products.xlsx`, etc.
- `ecommerce_products.db` – SQLite database storing all scraped products.

## ⚠️ Notes
- These websites have anti-bot measures, so **Selenium with random delays** is used.
- **Ensure you have Google Chrome installed** since Selenium requires it.
- Modify `URL` inside each scraper script to customize the product search.

## 📜 License
This project is open-source and available under the **MIT License**.

---

👨‍💻 **Author:** Clinton Yade  
📧 **Contact:** [Your Email or GitHub Profile]

