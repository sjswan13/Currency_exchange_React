Currency Exchange Rate Converter

This is a React-based currency exchange rate converter application that allows users to calculate exchange rates between different currencies. The app fetches real-time exchange rate data from the ExchangeRate-API and provides an intuitive user interface for converting between currencies.

Deployed with Nelify: https://visionary-mooncake-e78ce8.netlify.app

Table of Contents:

-Features
-Technologies Used
-Setup and Installation
-Usage
-Project Structure
-Future Improvements
-Contributing
-License
-Acknowledgements

Features:

-Real-time currency conversion using ExchangeRate-API.
-Support for multiple currencies.
-Simple and intuitive user interface.
-Swap functionality to easily switch between the "From" and "To" currencies.
-Responsive design 

Technologies Used:

-React: A JavaScript library for building user interfaces.
-CSS: For styling the application.
-ExchangeRate-API: To fetch real-time exchange rate data.

Setup and Installation:
To run this project locally, follow these steps:

Clone the repository:

git clone https://github.com/yourusername/currency-exchange-rate-converter.git
cd currency-exchange-rate-converter

Install dependencies:

Make sure you have Node.js installed. Then, run:
npm install

Start the development server:

npm start
The app should now be running at http://localhost:3000.

Usage:

-Select the currency you want to convert from and to using the dropdown menus.
-Enter the amount in the "From" currency field, and the equivalent amount will be automatically calculated and displayed in the "To" currency field.
-Use the "Swap" button to quickly switch the "From" and "To" currencies.

Project Structure:
The project has the following structure:

css
Copy code
├── public
│   ├── index.html
│   └── img
│       └── money.png
├── src
│   ├── components
│   │   └── ExchangeRateCalculator.jsx
│   ├── App.jsx
│   ├── index.jsx
│   ├── App.css
│   └── index.css
├── .gitignore
├── package.json
└── README.md

-App.jsx: The main application file that renders the ExchangeRateCalculator component.
-ExchangeRateCalculator.jsx: The core component that handles currency conversion logic and UI.
-App.css and index.css: CSS files for styling the application.


Acknowledgements
Thanks to ExchangeRate-API for providing the exchange rate data.
Fonts used: Google Fonts - Dosis and Mukta.
