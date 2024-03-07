## Automated Latest GO Downloader

This repository contains an automation script for downloading the latest Government Orders (GO) from the [Andhra Pradesh Teacher's Union website](https://www.aputf.org).

### Overview

This script is designed to automate the process of accessing the latest GO published on the Andhra Pradesh Teacher's Union website and downloading the associated PDF file. It uses Selenium WebDriver to interact with the website and perform the necessary actions.

### Features

- **Dynamic Navigation**: The script navigates through the website to locate the section containing the latest GO.
- **Automated Download**: It identifies the latest GO and initiates the download process automatically.
- **Customizable**: Users can modify the script to suit their specific requirements by adjusting the CSS selectors.

### Usage

1. Clone the repository.
2. Install Selenium WebDriver and the appropriate browser driver (e.g., ChromeDriver).
3. Open the `.side` file in Selenium IDE or convert it to your preferred scripting language.
4. Customize the script as needed, particularly the CSS selectors if the website structure changes.
5. Run the script in a Selenium WebDriver compatible environment.

### Script Details

The `.side` file contains a series of commands recorded using Selenium IDE. These commands include:

- Opening the website
- Navigating to the section containing the latest GO
- Clicking on the link to access the latest GO
- Downloading the associated PDF file
- Handling window operations (opening, closing, selecting)

### Disclaimer

The script in the main file is generated after doing a test case run using the selenium IDE.
This script is provided as-is and may require adjustments based on changes to the website structure or updates to Selenium. Use it responsibly and ensure compliance with the website's terms of use and any applicable laws or regulations.

### Author

This script was created & uploaded by Gokula Krishna, Ramu.
