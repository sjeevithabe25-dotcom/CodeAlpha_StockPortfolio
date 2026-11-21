 CodeAlpha Task 2 – Stock Portfolio Tracker

1.Project Overview:
        The Stock Portfolio Tracker is a simple Python-based application designed to calculate and manage stock investments. It allows users to enter stock names and their quantities and automatically calculates the total investment value based on predefined stock prices.
        This project demonstrates the practical application of Python programming concepts such as dictionaries, loops, conditional statements, user input, arithmetic operations and file handling.

2. Problem Statement:
        Managing multiple stock investments manually can be difficult and time-consuming. Investors need to calculate individual stock values and the overall investment amount.
        This project provides a simple solution by automating investment calculations and displaying the portfolio details in an organized format.

3. Project Objectives:
       - To develop a simple stock portfolio tracking application.
       - To store stock names and prices using Python dictionaries.
       - To accept stock names and quantities from users.
       - To calculate individual investment values.
       - To calculate the total investment amount.
       - To display portfolio information clearly.
       - To save investment details in a text file.

4. Features:
  1. Displays a list of available stocks and their prices.
  2. Accepts stock names from the user.
  3. Accepts the quantity of each stock.
  4. Checks whether the entered stock is available.
  5. Calculates individual stock investment values.
  6. Calculates the total investment amount.
  7. Displays the complete stock portfolio.
  8. Saves the portfolio report in a text file.

5. Stock Price Details:
          The application uses predefined stock prices stored in a Python dictionary.
Stock Name| Price
AAPL| $180
TSLA| $250
GOOGL| $140
MSFT| $400
AMZN| $190

These prices are sample values used for demonstrating the application.

6. Working Principle:
The program follows these steps:
  1. Start the Python application.
  2. Display the available stock names and prices.
  3. Ask the user to enter a stock name.
  4. Check whether the stock name is valid.
  5. Ask the user to enter the quantity.
  6. Calculate the investment value.
  7. Add the investment to the total amount.
  8. Repeat the process until the user enters "done".
  9. Display all selected stocks and their investment values.
  10. Calculate and display the total investment.
  11. Save the portfolio report in a text file.

7. Algorithm:
Step 1: Start the program.

Step 2: Create a dictionary containing stock names and prices.

Step 3: Initialize an empty portfolio and total investment as zero.

Step 4: Display all available stocks.

Step 5: Get the stock name from the user.

Step 6: If the user enters "done", stop accepting inputs.

Step 7: Otherwise, check whether the stock exists in the dictionary.

Step 8: If valid, get the quantity and calculate the investment value.

Step 9: Add the investment value to the total investment.

Step 10: Display the portfolio and total investment.

Step 11: Save the portfolio details in "portfolio.txt".

Step 12: Stop the program.

8. Mathematical Formula:
Individual Investment Value
Investment Value = Stock Price × Quantity
Total Investment Value
Total Investment = Sum of All Individual Investment Values

Example Calculation:
AAPL:
180 × 2 = $360

TSLA:
250 × 3 = $750

Total Investment:

$360 + $750 = $1,110

9. Sample Output:

===== STOCK PORTFOLIO TRACKER =====

Available Stocks:
AAPL : $ 180
TSLA : $ 250
GOOGL : $ 140
MSFT : $ 400
AMZN : $ 190

Enter stock name: AAPL
Enter quantity: 2
Stock added successfully!
Investment value: $ 360

Enter stock name: TSLA
Enter quantity: 3
Stock added successfully!
Investment value: $ 750

Enter stock name: done

===== YOUR STOCK PORTFOLIO =====

AAPL | Quantity: 2 | Value: $ 360
TSLA | Quantity: 3 | Value: $ 750

Total Investment: $ 1110

Portfolio saved successfully in portfolio.txt

10. Advantages:
        - Easy to use and understand.
        - Reduces manual calculation work.
        - Calculates investment values quickly.
        - Supports multiple stock entries.
        - Provides an organized portfolio report.
        - Saves investment details for future reference.

11. Limitations:
        - Stock prices are predefined.
        - Does not retrieve live stock market prices.
        - Does not connect to a stock trading platform.
        - The application is currently console-based.

12. Learning Outcomes:
   Through this project, I gained practical knowledge of:
        - Python dictionaries.
        - User input and output operations.
        - While loops and conditional statements.
        - Arithmetic calculations.
        - File handling.
        - Basic problem-solving techniques.

13. Conclusion:
         The Stock Portfolio Tracker was successfully developed using Python. It helps users calculate individual stock investment values and the total investment amount efficiently.
         This project provided practical experience in Python programming and demonstrated how basic programming concepts can be used to solve simple real-world problems.

Thank You!
