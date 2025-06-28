# Amazon Product Data Scraper

This project is an automated tool to scrape product data from Amazon using Selenium. It is designed to help users extract comprehensive information about products directly from Amazon's web pages for research, analysis, or personal use. The scraped data is stored in an Excel (.xlsx) sheet for easy access and further processing.

## Features

- Scrapes product details such as title, price, and number of reviews.
- Uses Selenium for robust browser automation and scraping.
- Currently focused on scraping laptop data (brands like HP and Lenovo) by applying Amazon filters.
- Automatically saves the extracted data into an Excel (.xlsx) file.
- Configurable scraping parameters for future flexibility.

## Requirements

- Python 3.7+
- Selenium
- Chrome WebDriver (or another browser driver)
- openpyxl
- Internet connection

## Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mearslanahmed/Amazon_Product_Data_Scraper.git
   cd Amazon_Product_Data_Scraper
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Set up Chrome WebDriver**
   - Download the appropriate ChromeDriver version for your Chrome browser from [here](https://chromedriver.chromium.org/downloads).
   - Add it to your system PATH or place it in the project directory.

## Usage

1. **Configure your scraping parameters**
   - The script is currently set up to scrape laptops (brands: HP, Lenovo) on Amazon with applied filters.
   - You can modify the search keywords or filters in the script for other categories or brands.

2. **Run the scraper**
   ```bash
   python scraper.py
   ```

   The script will open an automated browser, apply the necessary filters (e.g., "HP", "Lenovo"), and scrape the product data.

## Output

- The scraper will generate an Excel (.xlsx) file containing the extracted product data, including:
  - Product Title
  - Price
  - Number of Reviews

  The file will be saved in the project directory.

## Notes

- This tool is for educational and personal use only. Scrape responsibly and be aware of Amazon's Terms of Service.
- Excessive scraping may result in IP blocking or CAPTCHAs.
- For stability, do not run too many requests in a short time.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.


## Disclaimer

This project is not affiliated with Amazon in any way.

---
**Author:** [mearslanahmed](https://github.com/mearslanahmed)
