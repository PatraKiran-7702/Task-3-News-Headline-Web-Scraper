# 📰 News Headline Web Scraper

## 📌 Project Overview

This project is a Python-based Web Scraper that extracts the latest news headlines from a public news website using **Requests** and **BeautifulSoup**. The scraped headlines are displayed in the console and saved to both a `.txt` file and a `.csv` file for future use.

This project was developed as part of the **Python Developer Internship - Task 3**.

---

## 🎯 Objective

* Scrape top news headlines from a public news website.
* Store the extracted headlines in a text file.
* Save the data in CSV format for analysis.
* Learn the basics of web scraping, HTTP requests, and HTML parsing.

---

## 🛠 Technologies Used

* Python 3
* Requests
* BeautifulSoup4
* Pandas
* Jupyter Notebook

---

## 📂 Project Structure

```text
Task-3-News-Headline-Scraper/
│
├── news_scraper.ipynb
├── news_headlines.txt
├── news_headlines.csv
├── README.md
└── screenshots/
```

---

## 🚀 Features

* Fetches headlines from a news website.
* Uses HTTP GET requests.
* Parses HTML using BeautifulSoup.
* Removes duplicate headlines.
* Saves headlines to a `.txt` file.
* Saves headlines to a `.csv` file.
* Includes error handling with try-except.
* Displays total number of headlines scraped.
* Adds timestamp information in CSV output.

---

## 📥 Installation

Install the required libraries:

```bash
pip install requests beautifulsoup4 pandas
```

---

## ▶️ How to Run

1. Open the Jupyter Notebook.
2. Install the required libraries.
3. Run all cells in the notebook.
4. The scraped headlines will be displayed in the output.
5. Generated files:

   * `news_headlines.txt`
   * `news_headlines.csv`

---

## 📸 Sample Output

```text
TOP NEWS HEADLINES
==================================================
1. Headline Example 1
2. Headline Example 2
3. Headline Example 3
...
```

---

## 📚 Key Concepts Learned

* HTTP Requests
* GET Request Method
* Web Scraping
* HTML Parsing
* BeautifulSoup
* File Handling
* CSV Data Storage
* Exception Handling
