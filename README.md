# Invoice Generator

## Introduction

The Invoice Generator is a simple yet powerful tool built using Streamlit and Python. It allows users to generate invoices, insert data into a MySQL database, and print old bills. The project provides a user-friendly interface for creating, managing, and storing invoices locally on the user's machine.

## Features

- **New Bill Generation**: Users can create new bills by entering details such as person's name, address, product ID, name, quantity, and price per unit.
- **Database Insertion**: The tool enables users to insert bill data into a MySQL database for record-keeping and future reference.
- **Printing Old Bills**: Users can print old bills by entering the invoice ID, fetching the data from the database, and generating the invoice document.
- **Local Data Storage**: The Invoice Generator stores data locally on the user's machine, ensuring privacy and easy access to previous invoices.

## Installation

To use the Invoice Generator, follow these steps:

1. Clone the repository to your local machine:

2. Install the required dependencies:

3. Set up a MySQL database with the required schema. Update the database connection details in the `main.py` file.

## Usage

To use the Invoice Generator, run the `main.py` file and follow the prompts to perform the desired actions:
- Select an option from the dropdown menu to create a new bill, insert data into the database, or print an old bill.
- Enter the required details such as invoice ID, person's name, address, product ID, name, quantity, and price per unit.
- Click on the corresponding button to generate invoices or insert data into the database.



