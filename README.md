# InvoiceScanner

InvoiceScanner is a tool to OCR PDF invoices and extract specific fields to store in a SQL database. The extracted fields include:
- Invoicing Date
- Currency
- Price incl. VAT
- VAT Percentage
- Price without VAT
- Company Name

Additionally, user inputs include:
- Tax Section
- Remark

## Setup

This project uses Python and requires the following libraries:
- PyMuPDF
- pytesseract
- pandas
- sqlite3

## Usage

1. Clone the repository.
2. Install the required libraries.
3. Run the script to process PDF invoices.

## License

This project is licensed under the MIT License.