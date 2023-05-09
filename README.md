Title: Medical Analysis Bulletin Converter

Description:

This repository contains a Python script that converts a medical analysis bulletin in PDF format into a cleaned DOCX file and a structured CSV file. The script extracts specific data from the PDF and generates a cleaned DOCX file without sensitive information like names and email addresses. Then, the script creates a structured CSV file containing the extracted data for easy storage and processing.

Features:

Extracts specific data from medical analysis bulletins in PDF format.
Generates a cleaned DOCX file without sensitive information.
Converts the extracted data into a structured CSV file.
Uses pdfplumber for PDF text extraction and pandas for data manipulation.
Requirements:

Python 3.6 or later
pdfplumber
python-docx
pandas
Installation:

Clone the repository:

bash
Copy code
git clone https://github.com/marcelgrama/medical-analysis-bulletin-converter.git
Change to the project directory:

bash
Copy code
cd medical-analysis-bulletin-converter
Install the required packages:

Copy code
pip install -r requirements.txt
Usage:

php
Copy code
python index.py <pdf_path>
Replace <pdf_path> with the path to your medical analysis bulletin PDF file. The script will generate a cleaned DOCX file and a structured CSV file in the same directory as the input PDF file.

Example:

Copy code
python index.py path_to_pdf.pdf
This will generate example.docx and example.csv files in the same directory as the input PDF file.

License:

MIT License
