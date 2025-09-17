# 300 - Step 3: Speak and Code

Let's write a script to read a CSV file in Python.

**Voice Command**: "*Write code to input CSV files.*"

<img width="1600" height="705" alt="Image" src="https://github.com/user-attachments/assets/1472643f-1651-4689-94af-24b4d2ea4653" />

The prompt will be sent directly into Cursor AI, and it will automatically start writing the corresponding Python code. Cursor AI will generate the following Python code using pandas library to read the CSV file:

<img width="1600" height="1212" alt="Image" src="https://github.com/user-attachments/assets/2bf6dede-d032-48a6-a222-727edf8d150c" />

If you need to make changes, you can use voice commands like:

**Voice Command**: "*Load customers.csv file from current directory and for each row, print the customer’s name and email address.*"

<img width="1557" height="1600" alt="Image" src="https://github.com/user-attachments/assets/e4a27f8f-f7bc-4836-8b69-7d374ec6c70d" />

Let’s add a function that generates usernames from the customer’s name and email address:

**Voice Command**: "*Define a function named create_username that takes a person’s name and email address and generates a username with the format: first letter of first name, followed by last name, all lowercase.*"

Cursor AI will create the function like this:

<img width="1600" height="1564" alt="Image" src="https://github.com/user-attachments/assets/b34c7971-ce4b-413b-9146-1210fbbc3a58" />

You can further refine the function with additional commands, for example:

**Voice Command**: "*Ensure the first and last names are lowercase and use only the first character of the last name.*"

Next you can extract the state code from a customer’s address using regular expressions:

**Voice Command**: "*Write a function named get_state_code that extracts the state code from an address string using regular expressions.*"

This allows you to easily extract state information from the customer data.
