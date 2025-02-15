# Number Base Converter

This is a simple web application that allows users to convert numbers between different number systems, including Decimal, Binary, Octal, and Hexadecimal. The tool supports conversions in both directions, for example, from Decimal to Binary and Binary to Decimal.

## Features

- **Convert Decimal to Binary**: Converts a decimal number into its binary representation.
- **Convert Binary to Decimal**: Converts a binary number into its decimal equivalent.
- **Convert Decimal to Octal**: Converts a decimal number into its octal representation.
- **Convert Octal to Decimal**: Converts an octal number into its decimal equivalent.
- **Convert Hexadecimal to Binary**: Converts a hexadecimal number into its binary representation.
- **Convert Binary to Hexadecimal**: Converts a binary number into its hexadecimal equivalent.

## Requirements

- A modern web browser (Chrome, Firefox, Safari, etc.) that supports HTML, CSS, and JavaScript.
- No server-side technologies are required — the application works entirely in the browser.

## How to Use

1. **Select the Conversion Type**: Choose the type of conversion you want to perform (e.g., Decimal to Binary).
2. **Enter the Number**: Input the number you wish to convert into the appropriate field.
3. **Click 'Convert'**: After entering the number, click the "Convert" button to get the result.
4. **View the Result**: The converted value will be displayed below the input fields.

## Example

### Conversion: Decimal to Binary
1. Input: `10` (Decimal)
2. Click "Convert"
3. Result: `1010` (Binary)

### Conversion: Binary to Decimal
1. Input: `1010` (Binary)
2. Click "Convert"
3. Result: `10` (Decimal)

## How It Works

The Number Base Converter works by using basic mathematical formulas for each type of conversion:

- **Decimal to Binary**: Repeatedly divide the decimal number by 2 and record the remainders.
- **Binary to Decimal**: Multiply each digit in the binary number by the corresponding power of 2 and sum the results.
- **Decimal to Octal**: Repeatedly divide the decimal number by 8 and record the remainders.
- **Octal to Decimal**: Multiply each digit in the octal number by the corresponding power of 8 and sum the results.
- **Hexadecimal to Binary**: Convert each hexadecimal digit to its 4-bit binary equivalent.
- **Binary to Hexadecimal**: Group the binary digits in sets of four, and convert each group to its hexadecimal equivalent.

## Technologies Used

- **HTML**: For the structure of the web page.
- **CSS**: For styling and layout.
- **JavaScript**: For performing the base conversion operations and handling user interactions.

## Getting Started

To get started with the Number Base Converter, simply clone or download the repository and open the `index.html` file in your preferred web browser. No server setup is needed!

### Clone the repository:
```bash
git clone https://github.com/yourusername/number-base-converter.git
