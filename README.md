
# SpendWise - Budget Tracker

## Project Description

SpendWise is a simple budget management application
that helps users manage their money, record expenses,
calculate total spending, and monitor their remaining
budget.

## Improvements Made This Week

This week, I improved SpendWise by adding:

- Multiple expense entries.
- An expense list.
- Automatic calculation of total expenses.
- Automatic calculation of remaining balance.
- Budget warning messages.
- Input validation.
- Interactive buttons.

## JavaScript Concepts Implemented

### 1. Conditionals

I used if, else if, and else statements to check
whether the user is within their budget, has used
their entire budget, or has exceeded it.

### 2. Arrays

I used an array called expenses to store multiple
expense records.

Each expense contains a name and an amount.

### 3. DOM Manipulation

I used document.getElementById() to select HTML
elements and textContent to update information.

I also used createElement() and appendChild()
to display expenses on the webpage.

### 4. Events and User Interactions

I used addEventListener() to respond to button clicks.

Users can set their budget and add expenses by
interacting with the application.

### 5. Functions

I created functions to organize the JavaScript code.

- displayExpenses() displays the expense list.
- updateSummary() calculates and displays the budget summary.

## How Calculations Are Performed

The application adds all expenses together
and subtracts the total from the budget.

Remaining Balance = Budget - Total Expenses

## Challenges Encountered and Solutions

### Challenge 1: Storing Multiple Expenses

I initially had difficulty storing multiple expenses.

Solution: I used a JavaScript array and the push()
method to store each expense.

### Challenge 2: Updating the Webpage

I needed the expense list and budget summary to
update whenever a new expense was added.

Solution: I used DOM manipulation and functions
to update the webpage automatically.

### Challenge 3: Validating User Input

Invalid or empty values could affect calculations.

Solution: I used conditional statements to validate
the user's input before performing calculations.

## Technologies Used

- HTML5
- CSS3
- JavaScript

## Author

Sahro Yarow Ismail

## Project Name

SpendWise Budget Tracker
