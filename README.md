# Real_Time_Currency_Converter
(Python)

A simple and modern desktop application for real-time currency conversion, built with Python and Tkinter. Instantly convert between major currencies using live exchange rates fetched from an online API.

## Features
- Real-time currency conversion
- Clean and modern Tkinter GUI
- Supports USD, INR, EUR, BRL, and CAD
- Easy-to-use dropdowns for selecting currencies
- Instant result display with currency symbols
## How It Works
1. **First, select the currency you want to convert from.**  
<img width="300" height="400" alt="Screenshot 2025-07-19 220429" src="https://github.com/user-attachments/assets/a6505cd8-f547-4e06-9ee4-db9e7ba44cbf" />

2. **Next, select the currency you want to convert to.**  
<img width="300" height="400" alt="Screenshot 2025-07-19 220508" src="https://github.com/user-attachments/assets/9c72b7d9-f084-40ac-8ec2-0f8187e70c8e" />

3. **Enter amount and click the Convert button to perform the conversion.**  
<img width="300" height="400" alt="Screenshot 2025-07-19 220526" src="https://github.com/user-attachments/assets/4a4f8eff-1686-40ba-ae0c-9392f9f5f41d" />

4. **You can see the real-time converted amount in the rectangular box.**

## API Used
This application uses the [Currency Converter API by RapidAPI](https://rapidapi.com/). The endpoint used is:
https://currency-converter18.p.rapidapi.com/api/v1/convert

You need a RapidAPI key to use this API. The key is set in the code under the `headers` dictionary.

## How to Run
1. Make sure you have Python 3.x installed.
2. Install the required dependencies:
   ```bash
   pip install requests
   ```
3. Run the application:
   ```bash
   python Currency_Converter.py
   ```

## Customization
- To add more currencies, update the `currency` list in the code.
- To use your own API key, replace the value in the `headers` dictionary.

## License
This project is for educational purposes only. 
