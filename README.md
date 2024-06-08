# Web-Scraping
## Overview
This project is a comprehensive web scraping solution designed to extract news articles from the Business Recorder e-paper website. The scraping operation covers a period from January 2018 to March 2024, collecting and processing article data into a structured dataset for further analysis.
## Features
### Optimized HTTP Requests: 
Utilizes requests.Session to manage and optimize HTTP requests.
### Concurrent Scraping: 
Implements multithreading using concurrent.futures.ThreadPoolExecutor to scrape multiple articles concurrently, significantly speeding up the data collection process.
### Data Extraction: 
Uses BeautifulSoup to parse HTML and extract key information, including article titles, dates, URLs, and content.
### Robust Error Handling: 
Includes mechanisms to handle failed requests and ensure continuous scraping.
### Data Storage: 
Converts the collected data into a pandas DataFrame and saves it as a CSV file for easy access and analysis.
