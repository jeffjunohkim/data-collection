# data-collection

## Overview

This project involves two main exercises: scraping news articles from the Mars News Site and extracting and analyzing temperature and atmospheric pressure data from the Mars Facts website.

### Mars News Site Web Scraping

#### Overview:
This exercise involved scraping the latest news articles from the Mars News Site to extract the titles and preview text of each news article.

#### Steps Taken:

- **Set Up the Environment:**
  - Imported necessary libraries: Splinter and BeautifulSoup.
  - Initialized the browser using Splinter.

- **Visit the Mars News Site:**
  - Used Splinter to open the Mars News Site URL.

- **Scrape the Data:**
  - Created a BeautifulSoup object to parse the HTML content.
  - Extracted the titles and preview text of the news articles.
  - Stored each title and preview text pair in a dictionary with keys `title` and `preview`.
  - Appended each dictionary to a list.

- **Print the Results:**
  - Printed the list of dictionaries to verify the extracted data.

### Mars Table Data Web Scraping and Analysis

#### Overview:
This exercise involved scraping data from a table on the Mars Facts website and performing analysis on the scraped data. The goal was to extract, process, and visualize Mars temperature and atmospheric pressure data.

#### Steps Taken:

- **Set Up the Environment:**
  - Imported necessary libraries: Splinter, BeautifulSoup, matplotlib, and pandas.
  - Initialized the browser using Splinter.

- **Visit the Mars Facts Site:**
  - Used Splinter to open the Mars Facts Site URL.

- **Scrape the Data:**
  - Created a BeautifulSoup object to parse the HTML content.
  - Extracted all rows of data from the table.
  - Created a list of rows and defined column names.
  - Created a pandas DataFrame using the list of rows and column names.
  - Changed data types for analysis.

- **Analysis:**
  - Calculated and printed the number of months on Mars.
  - Calculated and printed the number of Martian days' worth of data.
  - Calculated the average minimum temperature by month and plotted the results.
  - Identified the coldest and hottest months.
  - Calculated the average atmospheric pressure by month and plotted the results.
  - Identified the months with the lowest and highest atmospheric pressure.

- **Export the Data:**
  - Exported the DataFrame to a CSV file

## Code Source
- Learning Assistant
- GitHub location: [https://github.com/jeffjunohkim/data-collection.git](https://github.com/jeffjunohkim/data-collection.git)
