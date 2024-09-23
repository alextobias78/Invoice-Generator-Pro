# Invoice Generator

A web-based invoice generation application built with Flask.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)
- [Contact](#contact)

## Features

- Create professional-looking invoices with a user-friendly web interface
- Customizable invoice details including business and client information
- Support for multiple line items with automatic calculations
- Option to add a company logo
- Flexible payment details (IBAN or other banking information)
- Automatic PDF generation with a clean, modern design
- Currency selection
- Tax rate customization
- Intelligent due date handling and display

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/alextobias78/invoice-generator.git
   cd invoice-generator
   ```

2. Create a virtual environment and activate it:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required dependencies:
   ```
   pip install flask reportlab Werkzeug
   ```

## Usage

1. Start the Flask development server:
   ```
   python app.py
   ```

2. Open a web browser and navigate to `http://localhost:5000`

3. Fill out the invoice form with the required information

4. Click "Generate Invoice" to create and download the PDF invoice

## Dependencies

- Flask
- ReportLab
- Werkzeug

For a complete list of dependencies, see the `requirements.txt` file.

## License

This project is open source and available under the [MIT License](https://opensource.org/license/mit).

## Contact

Created by [@alextobias78](https://github.com/alextobias78) - feel free to contact me!
