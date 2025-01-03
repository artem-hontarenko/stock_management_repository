# Stock management system

Stock Management System - a console-based Java application that allows users to manage their stock portfolio and make trading decisions based on real-time market data.
The system integrates with a financial API (such as Alpha Vantage or Yahoo Finance API) to fetch current share prices and market data. Users start by creating an account with an initial deposit of fiat currency. They can add more funds at any time using a simple deposit command. The system maintains a detailed record of all transactions, including deposits, share purchases, and sales. When users want to purchase shares, the system fetches real-time prices from the API and calculates the maximum number of shares they can buy with the particular amount of money the user are willing to spend. Similarly, when selling shares, the system uses current market prices to calculate the proceeds, which are automatically added to the user's balance.    

A key feature is the portfolio management system that provides comprehensive reports. Users can view their complete asset list, including both shares and fiat currency. For each shareholding, the system displays the quantity owned, purchase price, current market price, and the total value. This helps users track their investment performance easily.    

The analytical reporting feature provides insights into investment performance. It calculates profit/loss for each holding by comparing purchase prices with current market values, showing both absolute and percentage changes. 
