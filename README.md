# Inventory Management Spreadsheet Automation

This project automates inventory management tasks using Python and the openpyxl library. It reads data from an Excel spreadsheet, performs calculations, generates charts, and saves the updated data back to the spreadsheet.

## Table of Contents
- [Getting Started](#getting-started)
- [Features](#features)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

## Getting Started

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/your-username/inventory-spreadsheet-automation.git
    cd inventory-spreadsheet-automation
    ```

2. **Install Dependencies:**
    ```bash
    pip install openpyxl
    ```

3. **Run the Script:**
    ```bash
    python inventory_automation.py
    ```

## Features

1. **Products per Supplier:**
    - Calculates the number of products per supplier.

2. **Total Value per Supplier:**
    - Calculates the total value of inventory per supplier.

3. **Products with Inventory less than 10:**
    - Identifies products with inventory less than 10.

4. **Chart Generation:**
    - Generates a bar chart based on inventory prices.

5. **Save Updated Spreadsheet:**
    - Saves the modified data, including total inventory prices and chart, to a new Excel file.

## Usage

- Open the `inventory.xlsx` file with your inventory data in the root folder.
- Run the script using the instructions provided in the "Getting Started" section.
- Check the console for calculated results and the `inventory_with_total_value.xlsx` file for the updated spreadsheet.

## Dependencies

- [openpyxl](https://openpyxl.readthedocs.io/): A library for reading and writing Excel (xlsx) files.




