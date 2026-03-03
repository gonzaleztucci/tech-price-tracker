# TechPrice Tracker: PC Componentes 

This project is a **Python-based Price Tracker** designed to monitor price fluctuations for tech products. It combines automated web scraping with a relational database to provide historical data analysis, bridging my background in **Procurement & Supply Chain** with **Software Engineering**.

## Purpose
In industries like automotive or energy, monitoring market price volatility is crucial. This tool automates the tracking process, ensuring data-driven decision-making through:
* **Automated Scraping:** Extracting real-time prices from PC Componentes using `BeautifulSoup`.
* **Data Persistence:** Storing historical records in a **SQL** database to track trends over time.
* **Price Intelligence:** Comparing current data against historical averages to identify savings opportunities.

## Tech Stack
* **Language:** Python 3 (focused on automation and data handling).
* **Library:** `BeautifulSoup4` & `Requests` for web scraping.
* **Database:** **SQL** (SQLite) for robust data storage.
* **Environment:** Virtual environments for dependency management.

## Project Structure
```text
tech-price-tracker/
├── data/               # SQLite database storage
├── src/                
│   ├── scraper.py      # Scraping logic
│   ├── database.py     # SQL connection and queries
│   └── main.py         # App entry point & business logic
├── .gitignore          # Git exclusion rules
└── requirements.txt    # Project dependencies
```

## Setup

1. Clone the repo: `git clone https://github.com/gonzaleztucci/tech-price-tracker.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Run the tracker: `python src/main.py`