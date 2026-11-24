# Investment Calculator Application

## Overview
An investment application where a user can calculate the returns on a monetary investment over a user-specified number of years by inputting initial investment values.<br>
The app dynamically displays a table of results as the user adjusts values in the input fields.<br>
The app contains error handling to prevent users specifying 0 years and specifying negative values.<br>
There is also functionality to export the displayed results in a pdf file.<br>
The app makes use of a setTimeout function to simulate the loading of the pdf download, with a dialogue box that appears when this timer is running to let the user know that work is being done generating the pdf.<br>
This app was created using the Vite framework.<br>
A preview of what this project looks like when deployed can be viewed on Vercel at this link: https://investment-calculator-application-r.vercel.app/

## Tech Stack
- React.js
- Vite
- CSS3
- HTML5

## Project Structure
```
Investment-Calculator-Application-React/
└─public/
├    └─ vite.svg
└─src/
├    └─ assets/
├        └─ logo.jpg
├    └─ components/                    # React components for the structure of the page and operating the calculator.
├        ├─ Header.jsx
├        ├─ HeaderTitle.jsx
├        ├─ InvestmentCalculator.jsx
├        ├─ Output.css
├        ├─ Output.jsx
├        └─ UserInput.jsx
├    └─ util/                          # React components for the mathematical calculations and generating the report.
├        ├─ generatereport.jsx
├        └─ investments.jsx
├    ├─ App.css
├    ├─ App.jsx
├    ├─ index.css
├    └─ main.jsx
├─ README.md
├─ eslint.config.js
├─ index.html
├─ package-lock.json
├─ package.json
└─ vite.config.js
```
