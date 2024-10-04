# Cryptocurrency Price Tracking and Analysis using CoinMarketCap API

## Project Overview
This project involved developing an automated system to retrieve and analyze live cryptocurrency data using the CoinMarketCap API. The primary objective was to display trends and price changes for top cryptocurrencies and visualize both short-term and long-term percent changes in cryptocurrency prices. Data was logged in CSV format for further analysis.

## Key Responsibilities

### 1. Data Retrieval
- **Automated API Integration**: Developed a system to connect to the CoinMarketCap API and retrieve live cryptocurrency data.
- **Data Normalization**: Utilized Pandas to normalize the JSON data returned from the API for easier manipulation and analysis.

### 2. Data Analysis
- **Trend Analysis**: Analyzed short-term (1 hour, 24 hours) and long-term (7 days, 30 days, 60 days, 90 days) percent changes in cryptocurrency prices.
- **Visualization**: Employed Seaborn and Matplotlib to create visual representations of price trends, enabling clearer insights into cryptocurrency performance.

### 3. Data Logging
- **CSV Data Storage**: Implemented functionality to log API responses into a CSV file for ongoing tracking and analysis of cryptocurrency price trends.

### 4. Automation
- **Scheduled Data Retrieval**: Designed a loop to automatically retrieve data from the API at regular intervals (every 60 seconds) for a specified number of iterations.

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: Requests, Pandas, Seaborn, Matplotlib
- **Data Source**: CoinMarketCap API

## Outcomes
- Successfully developed an automated system to track live cryptocurrency prices and trends.
- Visualized significant price changes and trends, facilitating better understanding and analysis of market movements.
- Logged historical price data into CSV files, providing a foundation for further analysis and reporting.

## Conclusion
This project demonstrates the effectiveness of using APIs for real-time data retrieval and the importance of data visualization in analyzing cryptocurrency trends. Future enhancements could include implementing a user interface for more interactive data exploration and analysis.
