# Expense Tracker

A minimal client-side Expense Tracker web page to record simple transactions, view your balance, income, and expenses.

## Files

- ExpenseTracker.html — Main HTML UI
- ExpenseTracker.js — JavaScript logic (transaction handling, calculations)
- expensetracker.css — Styles

## Features

- Add transactions with a description and an amount.
- Use negative amounts for expenses and positive for income.
- Displays current balance, total income, and total expenses.

## Requirements

- A modern web browser (Chrome, Edge, Firefox, Safari).

## Run / Preview

1. Open `ExpenseTracker.html` directly in your browser.
2. Or serve the folder using a simple HTTP server (recommended for some browsers):

   ```bash
   python -m http.server 8000
   # then open http://localhost:8000/ in your browser
   ```

## Usage

- Enter a description and an amount, then click "Add Transaction".
- Use a negative value (e.g., `-25`) to record an expense.
- The app updates balance, income, and expense totals automatically.

## Development

- Edit `ExpenseTracker.js` to change behavior or persistence.
- Edit `expensetracker.css` to change styling.

## License

This project has no license specified. Add a license file if you plan to publish or share it.
