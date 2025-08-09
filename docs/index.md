# My Friend's Car Hunt: A Data Analysis Journey

## The Story Behind the Project

A good friend of mine figured she is in urgent need of a second-hand car. She was also adamant that she will get one through the **We Buy Cars** dealership. I tried to convince her to be diverse and check out other dealerships but no! She only trusts We Buy Cars.

So, trying to be helpful, I thought let me get her the data from the dealership website and save it in a spreadsheet to save her Browse time.

First, I tried to scrape the HTML data from the website using the **Requests** and **BeautifulSoup** libraries. But that led to a dead end because the site does not allow that. So now with a different approach, I will get the data using their hidden API.

## Project Description

This project is a data analysis of second-hand hatchback vehicles from the WeBuyCars dealership in South Africa. The project uses Python to scrape data, perform an initial assessment, and analyze the car market. The entire process is documented in a Jupyter Notebook (`buyCars.ipynb`).

## Project Goals

The primary objectives of this project were to:
* **Data Gathering:** Scrape second-hand hatchback vehicle data from the WeBuyCars website's API.
* **Data Assessment:** Evaluate the gathered data for missing values and data types.
* **Data Cleaning and Analysis:** Clean the data and perform an analysis to provide insights into the vehicle market.

## Tools and Libraries

The following Python libraries were used:
* `requests` for making API calls.
* `pandas` for data manipulation and analysis.
* `seaborn` and `matplotlib.pyplot` for data visualization.
* `os` for file system operations.

## Key Findings from Initial Assessment

During the initial data assessment, I found that the dataset contained 1920 entries and 92 columns. A significant number of columns contained null values, particularly those related to auctions, as only a small subset of the vehicles were on auction at the time of data collection. It was also noted that some numerical columns, like `NoGears`, were stored as strings and would require cleaning before analysis.

## Analysis and Report
>TO DO!
