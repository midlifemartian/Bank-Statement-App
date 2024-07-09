# Bank Statement Analyzer

## Introduction

The Bank Statement Analyzer is a Python-based application that extracts, parses, and analyzes transactions from PDF bank statements. It provides detailed analysis including negative balances, total revenue, deposit counts, repeating withdrawals, and average revenue for each month.

## Features

- Extract text from PDF bank statements
- Parse transactions and categorize them by month
- Analyze transactions to provide insights
  - Negative balances
  - Total revenue
  - Deposit count
  - Repeating withdrawals
  - Average revenue

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/bank_statement_analyzer.git
    ```

2. Navigate to the project directory:
    ```bash
    cd bank_statement_analyzer
    ```

3. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On macOS/Linux
    ```

4. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the `analyze_bank_statements.py` script:
    ```bash
    python analyze_bank_statements.py
    ```

2. Enter the path of the bank statement PDF when prompted:
    ```plaintext
    Enter the path of the bank statement PDF: /path/to/your/bank_statement.pdf
    ```

3. View the analysis results printed in the terminal.

## File Structure

```plaintext
bank_statement_analyzer/
│
├── app.py
├── analyze_bank_statements.py
├── templates/
│   ├── index.html
│   └── result.html
├── requirements.txt
└── README.md
