# Miniproject_C


Functions used in Bank Management System:
The source code for Customer Account Bank Management System is relatively short and easy to understand. I have divided this C mini project into many functions, most of which are related to different banking activities. Listed below are some of the more important functions which may help you understand the project better.

menu() – This function displays the menu or welcome screen to perform different banking activities mentioned below.


 
new_acc() – This function creates a new customer account. It asks for some  personal and banking details of the customer such as name, date of birth, citizenship number, address and phone number. You can enter the amount to deposit and choose one type of deposit account – saving, current, fixed for 1 year, fixed for 2 years or fixed for 3 years.

view list() – With this function, you can view the customer’s banking information such as account number, name, address and phone number provided while creating the account.

edit() – This function has been used for changing the address and phone number of a particular customer account.

transact() – With this function, you can deposit and withdraw money to and from a particular customer account.

erase() – This function is for deleting a customer account.

see() – This function shows account number, name, date of birth, citizenship number, age, address, phone number, type of account, amount deposited and date of deposit. It also displays the amount of interest corresponding to a particular account type.

In this bank management system project in C, file handling has been used for almost all functions. File has been used to store data related to new account, transaction, editing of account information and viewing of account information. I haven’t used file handling for the menu, interest calculation and password.
