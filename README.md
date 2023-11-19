# CSV to Excel Converter

This script converts data from a CSV file to an Excel file using the `openpyxl` and `csv` libraries.

## Prerequisites

- Python 3.x
- `openpyxl` library (Install using `pip install openpyxl`)

## Usage

1. Place the CSV file (`data.csv`) in the same directory as the script.
2. Run the script `main.py`.

## Description

The script performs the following steps:

1. Opens the CSV file for reading.
2. Reads the contents of the CSV file using `csv.DictReader` and converts it into a list.
3. Creates a new Excel workbook and activates the first sheet.
4. Populates the column headers in the Excel sheet.
5. Creates column labels using a list iterator.
6. Populates the data from the CSV file into the Excel sheet.
7. Saves the Excel workbook as `data.xlsx`.
8. Closes the workbook.