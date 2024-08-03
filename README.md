# Sales Report Clean-Up

This project is designed to clean and organize sales reports to ensure data integrity and usability. The goal is to automate the process of cleaning sales data, making it ready for analysis and reporting.

## Features

- **Data Parsing**: Extracts customer names, sales amounts, and thread colors from raw sales data.
- **Data Aggregation**: Calculates total sales and counts the number of threads sold by color.

## Getting Started

### Prerequisites

Make sure you have the following installed on your system:

- Python 3.7 or higher

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/BrayanCordero/sales-report-clean-up.git
    ```
2. Navigate to the project directory:
    ```bash
    cd sales-report-clean-up
    ```

### Usage

1. Place your raw sales data in the `daily_sales` variable in `main.py`.
2. Run the script:
    ```bash
    python main.py
    ```
3. Uncomment any of the `print` statements in `main.py` to get specific data:
    ```python
    # print(color_sales("white"))     
    # print(thread_sold)
    # print(customers)
    # print(sales)
    ```

## Code Overview

### `main.py`

This script processes the raw sales data and provides functionality to calculate the total sales and the number of threads sold by color.

