Name:Janani S Company: CodeAlpha ID:CA/03/41583 Domain :Java programming Duration: October 1.10.2024 - 31.10.2024 
Task-2(Stock Trading Platform )

Overview of the project:-
The **Simulated Stock Trading Platform** is a Java application that allows users to buy and sell stocks, manage their investment portfolio, and simulate real-time market conditions. Here's an overview of its key components and functionality:

### Features

1. **Stock Management**: 
   - The platform includes a predefined set of stocks (e.g., AAPL, GOOGL, TSLA, AMZN) with initial prices.
   - Users can view market data, including stock names and prices.

2. **Portfolio Management**: 
   - Users can create a portfolio with an initial balance.
   - The portfolio keeps track of owned stocks and their quantities, allowing users to see their current investments and remaining balance.

3. **Buying and Selling Stocks**: 
   - Users can buy stocks if they have sufficient balance and sell stocks they own.
   - The program validates transactions to ensure that users do not attempt to buy more than their balance allows or sell more shares than they own.

4. **Price Updates**: 
   - The platform simulates market volatility by randomly updating stock prices, adding realism to the trading experience.

5. **User Interaction**: 
   - A console-based menu allows users to navigate the platform easily. Options include viewing the market, buying/selling stocks, viewing the portfolio, updating prices, and exiting the program.

### Code Structure

- **Stock Class**: Represents individual stocks with properties for name and price. It includes methods for getting and setting the price and a string representation for display.

- **Portfolio Class**: Manages a user's stocks and balance. It handles buying and selling operations, along with displaying the current portfolio status.

- **TradingPlatform Class**: Acts as the main interface for users to interact with the market and their portfolio. It contains methods for displaying market data, processing buy/sell actions, updating stock prices, and displaying the portfolio.

- **Main Class**: The entry point of the program, which runs a loop allowing user interactions through the console.

### User Interaction

The application provides a straightforward interface that prompts users for inputs and displays relevant information based on their choices. This design helps users to easily manage their trading activities and monitor their investments.

### Overall Summary

The Simulated Stock Trading Platform serves as an educational tool for users interested in stock trading, offering a practical way to understand how buying and selling stocks works, while also learning about portfolio management in a risk-free environment.
