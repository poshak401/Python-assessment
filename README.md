# PYTHON ASSESSMENT

## Overview

This Python script demonstrates web interactions via Selenium, mobile operations via Appium, OCR image processing, and data manipulation. The script performs the following tasks:

1. **Selenium Web Automation:**
   - Navigates to an e-commerce website.
   - Performs a search for Hindi Books, scrapes data (name, price, rating), and organizes it into a structured format (JSON).

2. **Appium Mobile Automation:**
   - Sets up Appium to interact with a mobile application displaying a list of items with prices.
   - Takes a screenshot of the list of items within the app.

## Setup

1. Install Anaconda from [anaconda.com](https://www.anaconda.com/products/distribution).
2. Open Anaconda Navigator, create a new environment, and install the required packages using the provided `requirements.txt` file.

```bash
conda create --name automation_env python=3.8
conda activate automation_env
pip install -r requirements.txt
