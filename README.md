# Real-time Stock Watchlist

## Demo
Access and interact with the Real-time Stock Watchlist app below, or using this [_link_](https://stockwatchlist.streamlit.app/). To learn how to access the source code and build your own stock watchlist app keep reading!

## Overview
Stock Price Dashboard is a Python web application built using Streamlit that allows users to view real-time stock information for any given ticker symbol. This app leverages the Yahoo Finance API to fetch and display up-to-date stock price data, providing an intuitive and interactive experience for users interested in tracking stock market movements.

## Features
- Real-Time Data: Fetches and displays real-time stock price information using the Yahoo Finance API.
- Interactive Charting: Provides interactive and zoomable line charts for visualizing stock price movements throughout the current trading day.
- User-Friendly Interface: Easy-to-use text input for entering stock ticker symbols.
- Responsive Design: Adjusts column widths and vertical alignment for optimal user experience.
- Customizable Views: Automatically adjusts the y-axis to ensure the data is clearly visible.

## Installation
1. Clone the repository:
```sh
git clone https://github.com/arshchawla21/stock_watchlist.git
cd stock_watchlist
```
2. Install the required dependencies:
```sh
pip install -r requirements.txt
```
3. Run the Streamlit app:
```sh
streamlit run stock_app.py
```

## Usage
- Open the Streamlit app in your browser.
- Enter a stock ticker symbol (e.g., AAPL for Apple Inc.) in the input field.
- Click the "Refresh" button to fetch and display the latest stock price information.
- Use the interactive chart to zoom in and explore stock price movements.

## Dependencies
- streamlit: For building the web application interface.
- yfinance: For fetching real-time stock data from Yahoo Finance.
- pandas: For data manipulation and analysis.
- altair: For creating interactive and customizable charts.

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/arshchawla21/stock_watchlist/edit/main/LICENSE.md) file for more details.

## Acknowledgements
- The Yahoo Finance API for providing access to real-time stock data.
- The Streamlit team for creating an easy-to-use framework for building web applications.
