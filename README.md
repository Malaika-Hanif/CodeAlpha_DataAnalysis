# CodeAlpha_DataAnalysis
#  Web Scraping Project

This project was completed as part of my internship at **CodeAlpha**. It demonstrates how to scrape data from a multi-page website using Python, process the extracted information, and save it in a structured CSV format for further analysis.

##  Project Overview

The goal of this project was to automate the collection of data from multiple pages of a website. Instead of manually copying information, the scraper navigates through each page, extracts the required data, and stores it in a clean dataset.

##  Features

- Scrapes data from **50 web pages**
- Handles website pagination automatically
- Extracts structured information using **BeautifulSoup**
- Sends HTTP requests with the **requests** library
- Organizes and cleans data using **pandas**
- Exports the final dataset to a **CSV** file
- Automates the complete data collection process

##  Technologies Used

- Python
- requests
- BeautifulSoup (bs4)
- pandas

##  Project Structure

```
├── scraper.py          # Main scraping script
├── output.csv          # Scraped dataset
├── requirements.txt    # Required Python packages
└── README.md           # Project documentation
```

##  How It Works

1. Sends HTTP requests to the target website.
2. Parses the HTML content using BeautifulSoup.
3. Extracts the required data fields.
4. Automatically moves through all available pages.
5. Stores the extracted data in a pandas DataFrame.
6. Exports the final dataset as a CSV file.

## Project Results

- ✅ Scraped data from **50 pages**
- ✅ Collected **1000+ records**
- ✅ Automated the complete scraping workflow
- ✅ Exported the cleaned dataset to CSV

## Learning Outcomes

Through this project, I gained practical experience in:

- Web scraping with Python
- Handling HTTP requests and responses
- Working with pagination
- HTML parsing using BeautifulSoup
- Data cleaning and preprocessing
- Data storage using pandas
- Exporting structured datasets to CSV

##  Getting Started

### Clone the repository

```bash
git clone https://github.com/your-username/web-scraping-project.git
cd web-scraping-project
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the scraper

```bash
python scraper.py
```

The scraped data will be saved as `output.csv`.

##  Author

**Malaika Hanif**

Completed during the **CodeAlpha Internship**.
