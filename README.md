# FD_intrest
# Fixed Deposit Calculator

A simple **Fixed Deposit (FD) Calculator** built using **HTML, CSS, Bootstrap, and JavaScript**.

## Features

* Enter customer name
* Enter customer age
* Enter deposit amount
* Enter FD tenure
* Calculate interest based on age
* Calculate Simple Interest
* Deduct 2% from interest when interest is above ₹1,00,000
* Calculate total maturity amount
* Display the customer's name and maturity amount
* Reset the form

## Interest Rate

The interest rate is calculated based on the customer's age:

| Age                | Interest Rate |
| ------------------ | ------------: |
| 60 years and above |            8% |
| 40–59 years        |            7% |
| Below 40 years     |            6% |

## Formula

### Simple Interest

```text
Simple Interest = (Principal × Rate × Time) / 100
```

### Maturity Amount

```text
Maturity Amount = Principal + Simple Interest
```

## Technologies Used

* **HTML** — HyperText Markup Language
* **CSS** — Cascading Style Sheets
* **Bootstrap** — Front-end CSS framework
* **JavaScript** — Programming language used for calculation and DOM manipulation

## Project Structure

```text
Fixed-Deposit-Calculator/
│
├── index.html
├── fd.css
├── back.jpg
└── README.md
```

## How to Run

1. Download or clone the project.
2. Open the project folder in **Visual Studio Code**.
3. Open `index.html`.
4. Run the HTML file in a web browser.
5. Enter the required details.
6. Click **Calculate**.

## Example

```text
Name: Subbu
Age: 65
Amount: ₹100000
Tenure: 2 years
Interest Rate: 8%

Simple Interest:
(100000 × 8 × 2) / 100 = ₹16000

Maturity Amount:
₹100000 + ₹16000 = ₹116000
```

## Purpose

This project was created for practicing:

* HTML Forms
* Bootstrap Classes
* CSS Styling
* JavaScript Variables
* Conditional Statements
* Arithmetic Operators
* DOM Manipulation
* User Input Handling
* Simple Interest Calculation
