# Real Time Currency Converter

A real-time currency converter built with HTML, CSS, and JavaScript. This application fetches exchange rates from [exchangerate-api.com](https://www.exchangerate-api.com) and country flags from [flagsapi.com](https://flagsapi.com). By default, it shows the conversion from 1 USD to INR. If the user inputs 0 or leaves the input box empty, it automatically sets the value to 1 and displays the result. The application supports a list of 160 countries. It is also comes with responsiveness.

## Features

- Real-time currency conversion using exchange rates fetched from exchangerate-api.com.
- Displays country flags using flagsapi.com.
- Default conversion from 1 USD to INR.
- Handles zero or empty input by setting the value to 1.
- Supports conversion between 160 different currencies.
- Swap button to switch between 'from' and 'to' currencies with a smooth transition.
- Responsive.

## Files

- `index.html`: The main HTML file containing the structure of the currency converter.
- `style.css`: The CSS file for styling the currency converter.
- `script.js`: The JavaScript file containing the main logic for fetching data and updating the UI.
- `codes.js`: A JavaScript file containing the country codes and corresponding currency codes.

## Usage

1. Open `index.html` in your web browser.
2. Enter the value you want to convert in the input box.
3. Select the 'from' and 'to' countries from the dropdown lists.
4. Click the convert button to see the exchange rate.
5. Use the swap button to switch the 'from' and 'to' countries.


## Example

1. Enter the value: `1`
2. Select 'from' country: `United States (USD)`
3. Select 'to' country: `India (INR)`
4. Click the convert button to see the exchange rate.



## Acknowledgements

- Exchange rates provided by [exchangerate-api.com](https://www.exchangerate-api.com)
- Country flags provided by [flagsapi.com](https://flagsapi.com)
