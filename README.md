# We-Buy-Cars

# WeBuyCars Data Analysis

This Jupyter Notebook contains a data analysis project focused on second-hand hatchback vehicles from the WeBuyCars car dealership in South Africa. The project utilizes web scraping techniques to gather vehicle data and then performs an initial assessment and analysis using Python libraries like pandas, seaborn, and matplotlib.

## Project Goals

The primary objectives of this notebook are:
* **Data Gathering:** Scrape second-hand hatchback vehicle data from the WeBuyCars website.
* **Data Assessment:** Evaluate the gathered data for missing values and data types.
* **Data Cleaning and Analysis:** Clean the data and perform an analysis to provide insights into the vehicle market.
* **Reporting:** Generate a one-page PDF analysis report (this part is planned but not yet implemented in the provided code).

## Data Source

The data is scraped from the [WeBuyCars](https://www.webuycars.co.za/buy-a-car) website's API. The notebook specifically targets hatchback vehicles.

## Tools and Libraries

The following Python libraries are used in this project:
* `requests`
* `pandas`
* `seaborn`
* `matplotlib.pyplot`
* `os`
* `fpdf` (commented out, but planned for the PDF report)

## Key Findings from Initial Assessment

* The dataset contains 1920 entries and 92 columns.
* The data includes details such as `make`, `model`, `mileage`, `price`, `condition`, and various other technical specifications.
* There are a significant number of null values in columns related to auctions, as only a small subset of the vehicles were on auction at the time of data collection.
* Some columns that contain numerical data, such as `NoGears`, are currently stored as strings.

## Usage

1.  Ensure you have the required Python libraries installed.
2.  Run the notebook cells in sequence.
3.  The code will perform a POST request to the WeBuyCars API to gather data.
4.  The gathered data is stored in a pandas DataFrame called `car_trader`.
5.  You can uncomment the line `#car_trader.to_csv('weBuyCars.csv')` to save the DataFrame to a CSV file.

**Note:** The notebook mentions a plan to "Assess and clean the data. Analyse the data and provide a 1 page PDF analysis report". This part of the project is a "To Do" and is not fully implemented in the provided code.


![](usedCar.gif)
