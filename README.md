# Amazon Web Scraping Project

This project is a web scraping application built in Python with the assistance of YouTuber Alex the Analyst. The goal of this project is to extract product title and price information from Amazon's website, store the data in a CSV file, and implement functionality to check product prices on a daily basis.

## Overview

In this project, we utilized Python along with various libraries to scrape product information from Amazon. 

## Features

- **Web Scraping**: We used the BeautifulSoup library to parse HTML content and extract relevant product information such as title and price from Amazon's web pages.

- **CSV Data Storage**: With the help of the Pandas library, we organized the scraped data into a structured CSV file. This file serves as a database to store the extracted product information for further analysis.

- **Daily Price Checks**: The project includes functionality to automatically check product prices on a daily basis. This feature is implemented using the datetime and response libraries, enabling systematic monitoring of price fluctuations over time.

## Libraries Used

- **BeautifulSoup**: For HTML parsing and data extraction.

- **Datetime**: To handle date and time operations, particularly for implementing daily price checks.

- **Requests**: Used for making HTTP requests to fetch web page content.

- **Pandas**: For data manipulation and organizing scraped data into a CSV file.


## Acknowledgements

- Special thanks to YouTuber Alex the Analyst for the insightful tutorials and guidance on web scraping techniques using Python.



