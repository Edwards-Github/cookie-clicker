# Cookie Clicker Automation with Python

## Project Overview
This project automates the popular browser game Cookie Clicker using Python and Selenium. By simulating user clicks and automating upgrades, this script helps achieve higher scores faster without manual effort. It’s a fun way to explore browser automation while engaging with a lighthearted game.

## Features
- Automatically clicks the main cookie to generate cookies.
- Purchases upgrades and products when sufficient cookies are available.
- Continuously monitors cookie count and optimizes resource usage.
  
## Requirements
To run this project, you’ll need:
- Python 3.6 or later
- Google Chrome installed
- ChromeDriver compatible with your Chrome version
- Selenium library

## Installation
1. Clone this repository to your local machine
```
https://github.com/Edwards-Github/cookie-clicker.git
```
2. Install the required Python libraries:
```
pip install selenium
```
3. Download and place the appropriate `chromedriver.exe` in the project directory
```
https://googlechromelabs.github.io/chrome-for-testing/
```

## Usage
1. Run the script:
```
python cookie_clicker.py
```
2. The script will:
   - Open the Cookie Clicker game in a browser.
   - Automatically select the English language option.
   - Begin clicking the cookie and purchasing upgrades.

## How It Works
  - **Selenium WebDriver** : Controls the browser to interact with the game elements.
  - **XPath and ID Selectors** : Locate game elements like the cookie, upgrades, and product prices.
  - **Looping Mechanism** : Continuously clicks the cookie and evaluates upgrade purchases.

## Disclaimer
This project is for educational purposes only. Automating browser games may violate their terms of service, so use responsibly.

## Acknowledgments
Special thanks to [Tech With Tim](https://www.youtube.com/@TechWithTim) for the educational contentand to the Selenium community for their excellent resources.
