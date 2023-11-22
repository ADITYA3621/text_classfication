# text_classfication
The following Python script employs web scraping techniques along with logistic regression to extract and classify approximately 100 news articles from a news website based on the provided classifications. This script utilizes the BeautifulSoup library for web scraping and scikit-learn's logistic regression for classification.Script with 100 articles for training and testing, with 90% accuracy and 30% testing size of data.

# Scraping and Classification Application

This is a simple application that demonstrates web scraping, text cleaning, and text classification using machine learning. The application scrapes data from a website, cleans the text, and uses a logistic regression model to classify the text into different categories.

# Prerequisites

Before running the application, make sure you have the following dependencies installed:

Python (with dependencies)
Jupyter Notebook (optional)

Install Python depencies using:

pip install (dependency name)

# Website URL

The application is designed to scrape data from websites. Make sure you have internet access when running the application.
URL : https://www.npr.org/sections/news/

# CSS Selectors
Specify the CSS selectors for title and slug based on the structure of the website you are scraping.
You may need to inspect the HTML structure of your target website and adjust these selectors accordingly.

# execution
run the application using either run icon on jupyter notebook or by giving path of file with cmd command python text_classification.py

#evaluation report
The evaluation report will be stored in the "scrapped_data" folder as evaluation_report.csv.



