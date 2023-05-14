Project Description
This project is a command-line interface (CLI) tool that allows users to perform various operations on a given dataset. The tool supports various file formats and can perform operations such as filtering, sorting, and aggregating data.

How to Start the Command Interpreter
To start the command interpreter, follow these steps:

Clone the repository to your local machine
Install the required dependencies using pip install -r requirements.txt
Run the command python main.py to start the CLI.
How to Use the Command Interpreter
The command interpreter uses a simple syntax for executing commands. Each command consists of a keyword followed by one or more arguments. Here is the syntax for the commands:

command_name argument1 argument2 argument3 ...

Here are some examples of the supported commands:

load_file data.csv: Loads the data from the given CSV file.
filter age > 25 and gender = 'male': Filters the data to include only rows where age is greater than 25 and gender is male.
sort age: Sorts the data by the age column.
aggregate gender count: Aggregates the data by gender and counts the number of rows for each gender.
For a full list of supported commands and their syntax, see the documentation.

Examples
Here are some examples of how to use the command interpreter:

load_file data.csv: Loads the data from the file data.csv.
filter age > 25 and gender = 'male': Filters the data to include only rows where age is greater than 25 and gender is male.
sort age: Sorts the data by the age column.
aggregate gender count: Aggregates the data by gender and counts the number of rows for each gender.
