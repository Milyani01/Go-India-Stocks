# Go-India-Stocks
This repository contains a Python script for analyzing the buzz around "Green Hydrogen." The script includes web scraping of headlines from CNBC and Google News RSS, sentiment analysis, named entity recognition (NER), and integration with Google Sheets API for data storage. The analysis includes creating a CSV file, transferring data to a Google Sheet, plotting week-wise trends of sentiment scores, and generating a word cloud of organization names mentioned in the news headlines.

# Overview
This Python project aims to analyze the growing interest in "Green Hydrogen" by scraping headlines from CNBC and Google News RSS, performing sentiment analysis, named entity recognition (NER), and storing the results in a Google Sheet. The analysis includes creating a CSV file, visualizing week-wise trends of sentiment scores, and generating a word cloud of organization names mentioned in the news headlines.

# Requirements
Python 3.x

Libraries: beautifulsoup4, requests, transformers, pandas, gspread, oauth2client, matplotlib, wordcloud

# Data Sources
1. Web Scrape the following website
   https://www.cnbc.com/search/?query=green%20hydrogen&qsearchterm=green%20hydrogen
2. google news rss feed to get all news headline having “green hydrogen” as keyword
   https://news.google.com/rss/search?q=green%20hydrogen&hl=en-IN&gl=IN&ceid=IN:en

# Collaboratory Link
https://colab.research.google.com/drive/1zvhK4C3r-6sAYLybB9G0r9uc1wDnrOP_?usp=drive_link
