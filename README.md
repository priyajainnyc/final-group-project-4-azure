# Group-Project-3
Group-Project-4 for final challenge of module 23 of Datavis bootcamp

## Project Team
Soo Bin Im, Max Young, Meardreed Vilmeus, Priya Jain

# Project Title
Stock Predictions: To Bull or To Bear?

## Project Description: Stock Prediction Web Application using Dash and Machine Learning

This project aims to provide a simple yet effective tool for stock market investors to visualize company stock data and make predictions based on machine learning models. The web application is built using the Dash framework, a Python library for building web applications with interactive user interfaces.

## Project Structure

The project structure consists of the following files:

1. `importdash.py` - Main application file containing the Dash app instance and layout.
2. `model.py` - A helper file containing functions to fetch data from the yfinance library and to train and predict stock prices using a machine learning algorithm.
3. `assets/styles.css` - A file to style the webpage. 
4. `requirements.txt` - A file containing all the dependencies required to run the application.

We've provided three interactive visualizations in our dashboard to show the following data:  
  
**Visualizations**
- Quit, Hire and Job Opening Rates From 2001 - 2023: Line Chart 
- Annual Quit Rates for Top 5 Industries During Covid-19: Bar Chart
- Total Quit Rates by Industry During and After Recession: Bar Chart 
  
This interative dashboard explores the ["Bureau of Labor Statictics" dataset](https://www.bls.gov/). This dashboard contains charts to visualize BLS data that will allows us to better understand labor trends caused by major events such as the Covid-19 pendemic and the 2008 recession. 

## Built with
- Dash API, with HTML and CSS 
- Pandas
- Numpy
- Plotly
- yfinance
- Scikit-learn
- Tableau
- Azure Web Services

The dependencies can be installed by running the following command in your Python environment:

```
pip install -r requirements.txt
```

## Getting Started 
**Prerequisites**

Make sure you have installed all of the following prerequisites on your development machine:
- Your favorite code editor (e.g. VScode, etc.)
- Your favorite browser (e.g. Google Chrome, Firefox, etc.)

**Installation**
- Clone this repo and save it in your local directory
- git clone `https://github.com/priyajainnyc/group-project-4-azure`
- Open the repo in a code editor to see the codes
- Visit [localhost: 5000](http://localhost:5000) in your browser

## Usage

To use the application, simply run the `importdash.py` file in your Python environment and open a web browser to the specified address. The user will be presented with a single page interface, where they can enter a company stock code and a date range for which they would like to see the stock data plotted. 

Once the user enters the stock code and date range, the application will fetch the relevant stock data using the yfinance library and plot the stock price data. Additionally, the user can select an option to view predicted stock prices based on a machine learning algorithm trained on the historical data.

## Data Sources
- Yahoo! Finance API 
- [Bureau of Labor Statistics, Annual Average Quits Rates by Industry and Region, not Seasonally Adjuste](https://www.bls.gov/news.release/jolts.t22.htm)

## Conclusion

This project provides a simple yet powerful tool for investors to visualize and analyze stock data of a specific company using machine learning models. It is a great project for beginners to learn about web application development, data visualization, and machine learning in Python.
