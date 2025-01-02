Personal Accountant

A simple Python application to manage and track personal expenses. It allows users to input, view, and delete expenses, as well as display a summary of expenses by category.

Features:

Track New Expense: Allows users to input new expenses with the date, amount, category, and description.
View All Expenses: Displays all recorded expenses with their details.
View Expense Summary: Provides a summary of total expenses by category (e.g., food, entertainment, transport).
Delete All Expenses: Deletes all recorded expenses from the CSV file.
Persistent Data: Expenses are saved in an expenses.csv file, allowing data persistence.

Functions:

track_expense(): Tracks a new expense by taking user input and saving it to the expenses.csv file.
display_expenses(): Displays all expenses stored in the expenses.csv file.
display_summary(): Summarizes expenses by category.
delete_all_expenses(): Deletes all recorded expenses after user confirmation
..............................................................................

Telephone Directory

A simple Python application to manage contacts. It allows users to add, view, and delete contacts from a CSV file.

Features:

Add Contact: Allows users to add a new contact with name, phone number, and email.
View Contacts: Displays a list of all contacts saved in the CSV file.
Delete Contact: Allows users to delete a contact by name.
Persistent Data: Contacts are stored in a contacts.csv file, which maintains data even after the program ends.

Functions:

read_contacts(): Reads and returns all contacts from the contacts.csv file.
write_contact(): Adds a new contact to the contacts.csv file.
delete_contact(): Deletes a contact by name.
delete_all_contacts(): Deletes all contacts after user confirmation.
main(): Main loop to run the contact management system with various options.
