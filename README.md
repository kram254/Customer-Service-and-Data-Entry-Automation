# Customer-Service-and-Data-Entry-Automation
Customer Service and Data Entry Automation using Python and RPA

Sure, here's a possible README file for the two programs above:

RPA for Data Entry Automation
This repository contains two Python programs that demonstrate how to use RPA (Robotic Process Automation) to automate repetitive data entry tasks. The first program uses a custom library for data validation, while the second program uses the Pandas library for data validation.

## Requirements
Python 3.x
Pandas (if using the second program)
sqlite3
rpa
## Usage
Clone the repository to your local machine.
Install the required libraries using pip:
```
pip install pandas sqlite3 rpa
```
Prepare the input file in CSV format with the following columns: Name, Address, Phone, Email.
Modify the main() function in either program to specify the path to your input file and your SQLite database file.
Run the program using the following command:
```
python program_name.py
```
### Program 1: RPA with custom library
The rpa_custom_library.py program uses the data_extraction_library custom library to validate the data extracted from the input file. The library contains a validate() function that checks the data for missing values, incorrect data types, and other common data issues. If any errors are found, the program sends a notification message to the user.

### Program 2: RPA with Pandas
The rpa_pandas.py program uses the Pandas library to extract and validate the data from the input file. The program reads the input file into a Pandas DataFrame and uses Pandas' built-in data validation functions to check the data for missing values, incorrect data types, and other common data issues. If any errors are found, the program sends a notification message to the user.

## Output
Both programs insert the validated data into a SQLite database table named contacts. If the table does not exist, the program creates it. The table has four columns: name, address, phone, and email. The program inserts each row of data into the table as a new record.

## Contact
If you have any questions or suggestions about these programs, please contact me. Thank you for your interest!
