# Fundamental Booster

A simple interactive Python script that collects basic personal data from the user and displays each value along with its Python type and memory address.

## Features

- Prompts the user for their name, age, height, and favourite number
- Prints the entered values
- Shows the Python data type for each value
- Displays the memory address of each value
- Calculates an approximate birth year based on the entered age

## Requirements

- Python 3.x

## Usage

1. Open a terminal in the project folder.
2. Run the script:

```bash
python "fundamental booster.py"
```

3. Follow the prompts and enter:
   - your name
   - your age
   - your height in meters
   - your favourite number

## Example

```text
Welcome to the Interactive Personal Data Collector!

Please enter your name: Alex
Please enter your age: 30
Please enter your height in meters: 1.75
Please enter your favourite number: 7

Thank you! Here is the information we collected:

Name: Alex (Type: <class 'str'> , Memory Address: 139717... )
Age: 30 (Type: <class 'int'> , Memory Address: 139717... )
Height: 1.75 (Type: <class 'float'> , Memory Address: 139717... )
Favourite Number: 7 (Type: <class 'int'> , Memory Address: 139717... )

Your birth year is approximately: 1996 (based on your age of 30)

Thank you for using the Personal Data Collector. Goodbye!
```

## Notes

- The birth year is an approximation and does not account for the current date or the user's birth month.
- The memory address values will differ each time the script runs.
