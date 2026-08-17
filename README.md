# E-Commerce Inventory Sanctuary

## Project Description

This project demonstrates how JavaScript can clean messy inventory data before displaying it on a webpage. The original inventory array contains valid product names as well as empty strings, whitespace-only strings, incorrect data types, an undefined value, and an unknown product placeholder.

## How It Works

The `cleanData()` function uses the JavaScript `.filter()` method to create a new array containing only valid product name strings. The function removes non-string values, empty or whitespace-only strings, and the `"UNKNOWN_PRODUCT"` placeholder.

After the data is cleaned, a `.forEach()` loop creates HTML list items and displays the valid products on the webpage when the user clicks the **Run Data Purge & Render** button.

## Valid Products

* Wireless Mouse
* Mechanical Keyboard
* Ultrawide Monitor
* USB-C Charging Cable
* Ergonomic Office Chair

## Testing

The application was tested to verify that exactly five valid products are displayed, blank and whitespace-only values are removed, and invalid values such as `404` and `undefined` do not appear in the sanitized inventory.

## AI Assistance

AI was used to help develop and review the JavaScript cleaning logic. The AI was asked to provide two approaches for cleaning the messy array: a standard `for` loop and the `.filter()` method. The `.filter()` approach was selected because it provides a clean and beginner-friendly way to remove invalid data.

## How to Run

Download or clone the repository and open `data-cleaner.html` in a web browser. Click **Run Data Purge & Render** to clean and display the inventory.
