# Exchange-Rate-Calculator

This is a simple web-based exchange rate calculator that allows users to convert between different currencies. It fetches real-time exchange rate data from an external API and provides an easy-to-use interface for currency conversion. Here's how to use it and a brief overview of the project.

## Features
- Convert between various currencies.
- View the current exchange rate between the selected currencies.
- Swap the currencies with a single click.
- Real-time exchange rate data from an external API.

## How to Use
01. Select the source currency from the left dropdown (Currency One).
02. Enter the amount you want to convert in the input field next to Currency One.
03. Select the target currency from the right dropdown (Currency Two).
04. The converted amount will be displayed in the input field next to Currency Two.
05. To swap the source and target currencies, click the "Swap" button.

## Demo
[Exchange Rate Calculator](#your-live-demo-link)

## Technologies Used
- HTML
- CSS (Styling)
- JavaScript (Functionality)
- [ExchangeRate-API](https://www.exchangerate-api.com/) for fetching real-time exchange rate data.

API Key
This project uses the ExchangeRate-API to fetch exchange rate data. To use this API, you may need to sign up for a free API key on their website and replace the API endpoint in the main.js file with your own key.

```javascript
fetch(`https://v6.exchangerate-api.com/v6/YOUR_API_KEY/latest/${currency_one}`)
```

## Credits
- Currency exchange rate data is provided by [ExchangeRate-API](https://www.exchangerate-api.com/).

## Author
[Supun Gunawardhana](https://www.linkedin.com/in/supun-gunawardhana-b7a511261/)
