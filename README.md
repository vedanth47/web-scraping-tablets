# web-scraping-tablets
A Python web scraping project that extracts tablet product names, prices, and descriptions from a demo e-commerce website using Requests, BeautifulSoup, and Pandas.
# Web Scraping Tablets

A Python web scraping project that extracts tablet product information from a sample e-commerce website using Requests, BeautifulSoup, and Pandas.

## Overview

This project demonstrates how to retrieve webpage content, parse HTML, extract product details, and organize the collected data using Python.

## Features

- Fetch webpage content using Requests.
- Parse HTML using BeautifulSoup.
- Extract tablet product names, prices, and descriptions.
- Store scraped information in a Pandas DataFrame.
- Export the results to a CSV file.

## Technologies Used

- Python
- Jupyter Notebook
- Requests
- BeautifulSoup4
- Pandas

## Target Website

[Web Scraper — Tablets Test Site](https://webscraper.io/test-sites/e-commerce/allinone/computers/tablets)

This is a test website intended for learning and practicing web scraping.

## Installation and Usage

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/web-scraping-tablets.git
cd web-scraping-tablets
```

Replace `YOUR-USERNAME` with your GitHub username.

### 2. Install dependencies

```bash
pip install -r requirements.txt
```

### 3. Run the notebook

Open `inspect.ipynb` in Jupyter Notebook or VS Code and execute the cells in order.

### 4. View the output

The project is intended to save the extracted tablet information to `tablets_data.csv`.

## Project Structure

```text
web-scraping-tablets/
├── inspect.ipynb
├── requirements.txt
├── README.md
├── .gitignore
└── tablets_data.csv  # Generated output, if saved
```

## Learning Objectives

- Understand HTTP requests and status codes.
- Learn HTML parsing and element selection.
- Practice extracting structured information from webpages.
- Work with Pandas and CSV files.

## Disclaimer

This project is intended for educational purposes. Use the target website responsibly and respect its terms of use.

## Author

Add your name and GitHub profile here.
