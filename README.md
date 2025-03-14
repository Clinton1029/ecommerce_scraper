# 📦 Alibaba E-Commerce Scraper

## 🚀 Project Overview
This project is a **web scraper** for extracting product details from **Alibaba** using **Selenium and BeautifulSoup**. The scraper fetches product names, prices, ratings, and supplier details and saves them in **CSV, Excel, and SQLite database**.

## 📌 Features
- ✅ Scrapes the first **50 products** from Alibaba.
- ✅ Uses **Selenium** to bypass JavaScript-based loading.
- ✅ Saves data in **CSV, Excel, and SQLite database**.
- ✅ Implements **randomized delays** to mimic human behavior.

## 📂 Project Structure
```
Ecommerce_Scraper/
│── data/                 # Folder for storing extracted data (CSV, Excel, SQLite)
│── scripts/
│   ├── alibaba_scraper.py # Main script for scraping Alibaba products
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

### 4️⃣ **Run the Scraper**
```bash
python scripts/alibaba_scraper.py
```

## 📊 Output
- `data/alibaba_products.csv` – CSV file with scraped products
- `data/alibaba_products.xlsx` – Excel file with product details
- `data/alibaba_products.db` – SQLite database storing products

## ⚠️ Notes
- Alibaba has anti-bot measures, so **Selenium with random delays** is used.
- **Ensure you have Google Chrome installed** since Selenium needs it.
- Modify `URL` inside `alibaba_scraper.py` for different product searches.

## 📜 License
This project is open-source and available under the **MIT License**.

---

👨‍💻 **Author:** Clinton Yade  
📧 **Contact:** [Your Email or GitHub Profile]

