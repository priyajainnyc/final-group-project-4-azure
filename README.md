# Group-Project-4
Group-Project-4 for final challenge of module 23 of Datavis bootcamp

## Project Team
Soo Bin Im, Max Young, Meardreed Vilmeus, Priya Jain

# Project Title
Stock Predictions: To Bull or To Bear?

## Project Description: Stock Prediction Web Application using Dash and SVR Machine Learning

This project aims to provide a simple yet effective tool for stock market investors to visualize company stock data and make predictions based on machine learning models. The web application is built using the Dash framework, a Python library for building web applications with interactive user interfaces.

## Project Structure

The project structure consists of the following files:

1. `app.py` - Main application file containing the Dash app instance and layout.
2. `model.py` - A helper file containing functions to fetch data from the yfinance library and to train and predict stock prices using a machine learning algorithm.
3. `assets/styles.css` - A file to style the webpage. 
4. `requirements.txt` - A file containing all the dependencies required to run the application.


## Built with
- Dash API, with HTML and CSS 
- Flask
- Python
- Pandas
- Numpy
- Plotly
- yfinance
- nltk 
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
- Visit [localhost: 8050](http://127.0.0.1:8050/) in your browser
- Azure Web Services 'https://stock-predictions-rev.azurewebsites.net'

## Usage

To use the application, simply run the `app.py` file in your Python environment and open a web browser to the specified address. The user will be presented with a single page interface, where they can enter a company stock code and a date range for which they would like to see the stock data plotted. 

Once the user enters the stock code and date range, the application will fetch the relevant stock data using the yfinance library and plot the stock price data. Additionally, the user can select an option to view predicted stock prices based on a machine learning algorithm trained on the historical data.

## AI Stock Analysis (72 Selected Stocks)

We've provided the below listed visualizations for AI specific stock data pulled from Finviz in a Tableau dashboard as well as a sentiment analysis from the nltk library data:  
  
**Visualizations**
- Market Cap With Team Recommendation Category 
- Stock Current vs. Target Price 
- Number Of Employees By Sector
- Sales & Profit Margin % With Team Recommendation Category 
- EPS Growth With Team Recommendation Category 
- Performance % Past Year With Team Recommendation Category 
- Target vs. Current Price With Team Recommendation Category 
- Stock Price 52 Week Hi, Lo, Current vs. Target Price
- Sentiment Analysis

## Conclusion

This project provides a simple yet powerful tool for investors to visualize and analyze stock data of a specific company using machine learning models. It is a great project for beginners to learn about web application development, data visualization, and machine learning in Python and Tableau.

## Data Sources
- Yahoo! Finance API 
- NLTK Library
- Finviz
