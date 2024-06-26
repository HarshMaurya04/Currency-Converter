
# # Currency-Converter

## Overview

This is a dynamic Currency Converter application developed using HTML, CSS, and JavaScript. The application allows users to enter an amount in one currency and convert it to another currency of their choice. The converted amount is then displayed on the webpage. The project utilizes a currency API to fetch the exchange rates for accurate conversions.

## How to Use

**1] Enter Amount:** The user inputs the amount of money they wish to convert.

**2] Select Currencies:** Choose the currency you are converting from and the currency you want to convert to from the dropdown menus.

**3] Convert:** Upon clicking the provided button, the application fetches the exchange rate from the currency API.

**4] Display Result:** The converted amount is calculated and displayed on the webpage. 

## Technical Details

- **HTML:** Provides the structure of the application, including input fields, dropdown menus for currency selection, and a button to trigger the conversion.

- **CSS:** Styles the application, ensuring a clean and user-friendly interface.

- **JavaScript:** Contains the logic to handle user input, fetch exchange rates from the currency API, perform the conversion, and update the DOM to display the result.

- **Currency API:** Used to retrieve exchange rates for various currencies.

Endpoint:

```bash
/currencies/{currencyCode}

https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/eur.json
```

## Screenshots

![Screenshot 2024-06-26 194231](https://github.com/HarshMaurya04/Currency-Converter/assets/139550654/c754d70e-4d20-41bf-b8c2-f594964d39f8)

![Screenshot 2024-06-26 194405](https://github.com/HarshMaurya04/Currency-Converter/assets/139550654/6fe5fd51-e545-4731-ad73-60e062c678c9)

![Screenshot 2024-06-26 194759](https://github.com/HarshMaurya04/Currency-Converter/assets/139550654/adba2da4-9928-495d-bc78-8ac0f674e00a)
