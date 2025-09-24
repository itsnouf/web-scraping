
# Pokémon Web Scraping & EDA Project

## 📌 Project Overview

This project demonstrates how to perform **web scraping** and **exploratory data analysis (EDA)** using Python.
We scrape product data from the [ScrapeMe Pokémon Shop](https://scrapeme.live/shop/) and analyze it with **pandas**.

## 🛠️ Tech Stack

* **Python 3**
* **Libraries**:

  * `requests` → fetch web pages
  * `BeautifulSoup` → parse HTML and extract data
  * `pandas` → data cleaning, analysis, and CSV export
  * `matplotlib` → basic visualizations

## 📂 Project Structure

```
📦 pokemon-scraping-project
 ┣ 📜 Week3Task1WebScrapping.py      # Script for web scraping & saving data
 ┣ 📜 EDA.py            # Script for exploratory data analysis
 ┣ 📜 pokemon.csv       # Scraped dataset (exported CSV)
 ┣ 📜 README.md         # Project documentation
```

## 🔍 Features

* Scrapes product details (name, price, description, etc.) from all characters pages
* Stores data in a **CSV file** (`pokemon.csv`)
* Performs **basic EDA**:

  * Data cleaning & preprocessing
  * Histograms and pie charts for key features
  * Duplicate & missing values check

## ▶️ How to Run

### 1. Clone the Repository

```bash
git clone [https://github.com/itsnouf/web-scraping/tree/main]
cd web-scraping
```

### 2. Install Dependencies

```bash
pip install requests pandas beautifulsoup4 matplotlib
```

### 3. Run Web Scraping

```bash
python scraping.py
```

This will create `pokemon.csv` with all product data.

### 4. Run EDA

```bash
python eda.py
```

## 📊 Example Insights

* Average product price across all Pokémon
* Top 10 most common Pokémon products
* Distribution of prices

## 📌 Future Improvements

* Add **more advanced visualizations** using Seaborn/Plotly
* Build a **Streamlit dashboard** for interactive analysis

## 👨‍💻 Author

* Nouf Almutiri
* GitHub: [itsnouf]((https://github.com/itsnouf))

