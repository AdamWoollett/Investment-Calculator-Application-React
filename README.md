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
Investment-Calculator-Application-React/
└─public/<br>
&emsp;&emsp;└─ vite.svg<br>
└─src/<br>
&emsp;&emsp;└─ assets/<br>
&emsp;&emsp;&emsp;&emsp;└─ logo.jpg<br>
&emsp;&emsp;└─ components/<br>
&emsp;&emsp;&emsp;&emsp;├─ Header.jsx<br>
&emsp;&emsp;&emsp;&emsp;├─ HeaderTitle.jsx<br>
&emsp;&emsp;&emsp;&emsp;├─ InvestmentCalculator.jsx<br>
&emsp;&emsp;&emsp;&emsp;├─ Output.css<br>
&emsp;&emsp;&emsp;&emsp;├─ Output.jsx<br>
&emsp;&emsp;&emsp;&emsp;└─ UserInput.jsx<br>
&emsp;&emsp;└─ util/<br>
&emsp;&emsp;&emsp;&emsp;├─ generatereport.jsx<br>
&emsp;&emsp;&emsp;&emsp;└─ investments.jsx<br>
&emsp;&emsp;├─ App.css<br>
&emsp;&emsp;├─ App.jsx<br>
&emsp;&emsp;├─ index.css<br>
&emsp;&emsp;└─ main.jsx<br>
├─ README.md<br>
├─ eslint.config.js<br>
├─ index.html<br>
├─ package-lock.json<br>
├─ package.json<br>
└─ vite.config.js<br>
