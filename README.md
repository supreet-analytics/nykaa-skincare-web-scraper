# 🧼 Nykaa Skincare Web Scraper

## 📌 Overview

This project is a Python-based **web scraping solution** that collects real-time skincare product data from **Nykaa**, India’s leading beauty e-commerce platform.

Initially tested on a **sample product** (*Simple Kind To Skin Refreshing Facial Wash*), the logic was extended to dynamically scrape **multiple products** with fresh data every time the function is executed. The scraper extracts and cleans data, handles timestamps using the `datetime` module, and prepares structured tables for analysis.

---

## 🎯 Project Goals

- 🧪 Scrape product data from Nykaa for 50+ skincare items.
- 🔁 Automate data refresh each time the function is run.
- 📊 Prepare clean, structured data suitable for analysis.
- 🧼 Track discounts, ratings, and pricing trends across products.
- 🕒 Handle time-based elements like update timestamps using `datetime`.

---

## ⚙️ Technologies Used

| Library        | Purpose                                      |
|----------------|-----------------------------------------------|
| `requests`     | Fetching HTML content from URLs               |
| `BeautifulSoup`| Parsing and navigating HTML                   |
| `re` (regex)   | Cleaning and extracting patterns from text    |
| `pandas`       | Creating and analyzing tabular data           |
| `datetime`     | Timestamping and handling time-based logic    |
| `Jupyter Notebook` | Code execution and result visualization  |

---

## 📑 Data Points Extracted

- 🗂 Product Category
- 🕒 Last Updated Timestamp
- 🧴 Product Title (Cleaned)
- 📦 Size / Quantity
- 💰 Price (MRP and discounted)
- 🎯 Discount %
- ⭐ Ratings
- 👥 Rating Count

---

## 🧠 Key Highlights

- ✅ Started with one sample product to build logic.
- ✅ Dynamically scrapes and updates data for 50+ products.
- ✅ Clean tabular output using `pandas`, ready for export or further processing.
- ✅ Uses `datetime` to timestamp each run — useful for automation & tracking.
- ✅ Useful for dashboards, price tracking, competitor analysis, and more.

---

```markdown
## 📦 How to Run: Make sure required libraries (pandas, requests, bs4) are installed.

You can either:
- ✅ Open the `.ipynb` file directly in Jupyter Notebook and run the cells step-by-step  
**OR**
- 💻 Clone the repo:
  ```bash
  git clone https://github.com/yourusername/nykaa-web-scraper.git
  cd nykaa-web-scraper

---

> 💬 Feel free to clone this repo and try it with your own data. Contributions welcome!
