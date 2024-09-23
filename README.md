# Bank Information Database

This project contains a comprehensive database of various banks in Indonesia, including their names, bank codes, and customer service contact numbers.

## Overview

The bank information database is designed to provide easy access to important details about banks operating in Indonesia. This can be useful for developers, businesses, or anyone seeking to understand banking options in the country.

## Data Structure

The database consists of a JSON array, where each entry contains the following fields:

- **Name**: The name of the bank.
- **Bank Code**: The unique code assigned to the bank.
- **Call Center**: The customer service contact number.

### Example Entry

```json
{
    "Name": "Bank BRI (Bank Rakyat Indonesia)",
    "Bank Code": "002",
    "Call Center": "1500017"
}

fetch('path/to/your/bank-data.json')
    .then(response => response.json())
    .then(data => {
        console.log(data); // Access bank data here
    });

Feel free to customize any sections to better fit your project's needs!
