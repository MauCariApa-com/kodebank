# Bank Information Database

This project contains a comprehensive database of various banks in Indonesia, including their names, bank codes, and customer service contact numbers.

## Overview

The bank information database is designed to provide easy access to important details about banks operating in Indonesia. This can be useful for developers, businesses, or anyone seeking to understand banking options in the country.

## Data Structure

The database consists of a JSON array, where each entry contains the following fields:

- **name**: The name of the bank.
- **code**: The unique code assigned to the bank.
- **call**: The customer service contact number.

### Example Entry

```json
{
    "name": "Bank BRI (Bank Rakyat Indonesia)",
    "code": "002",
    "call": "1500017"
}
```
```js
fetch('path/to/your/kodebank.json')
    .then(response => response.json())
    .then(data => {
        console.log(data); // Access bank data here
    });
```

Feel free to customize any sections to better fit your project's needs!

## Credit
- MauCariApa.com
