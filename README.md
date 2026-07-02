# Grocery Splitter

A lightweight web app for splitting grocery bills item by item among roommates.

The app is built with plain HTML, CSS, and JavaScript. There is no backend, login, build step, or dependency install. Open `index.html` in a browser and use it.

## Features

- Add and manage roommates
- Add grocery items with category, price, payer, and shared-by selection
- Select everyone for an item with the row-level **All** checkbox
- Calculate each person's owed amount, paid amount, and final balance
- Show the overall grocery total for receipt checking
- Generate a simple settlement plan
- Switch currency display between USD, INR, EUR, and GBP
- Save progress in the browser with local storage
- Load demo data, export CSV, print, and reset

## How It Works

1. Add the people sharing groceries.
2. Build the table.
3. Add items with prices and the person who paid.
4. Select who shared each item, or use **All** for everyone.
5. Review the per-person totals, overall total, and settlement plan.

## Project Structure

```text
grocery-splitter/
  index.html  # Complete app: markup, styles, and JavaScript
  README.md   # Project notes
```
