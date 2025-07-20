# Electricity_Billing_System-master
• About  

This is a Java Swing-based GUI application for managing electricity billing, developed using IntelliJ IDEA. It integrates with a MySQL database via JDBC to perform CRUD operations related to customer billing, payments, and history.

or

It's a Java-based GUI application that lets users log in, add customer details, calculate electricity bills, generate bills, and process payments. The system uses Java Swing for the interface and JDBC to interact with a MySQL database.

or

The Electricity Billing System is a Java application that helps manage electricity bills for customers, just like a mini version of what electricity companies use. It allows the user (like an admin or employee) to handle everything digitally – from adding new customers to generating and paying bills.

• Technologies -

Java (Swing) – for GUI components
JDBC – to connect Java with MySQL
MySQL – as the backend database
IntelliJ IDEA – as the development environment

• Works 

1- Admin opens the app and logs in.
2- Adds a customer who just got a new meter.
3- After a month, admin enters the number of units the customer used.
4- The app calculates the bill using tax and charges.
5- The customer pays the bill.
6- Admin can generate and print/download the bill.

• Key Features 

• Login System
A secure page where the user logs in with a username and password.
Only logged-in users can use the system.

• Add Customer Details
You can save information like the customer’s name, address, city, email, phone number, and meter number.
This is useful to know who the bill is for.

• Calculate Bill
The user enters how many units the customer used in a month.
The system calculates the total bill using fixed charges and taxes (from the database).
It automatically saves this bill in the system.

• Generate Bill
The app shows a clean, formatted bill for any customer.
It includes customer info, month, units used, and the total amount.

• Pay Bill
Shows a list of unpaid bills.
The admin can mark bills as "paid" once payment is done.

• View Last Bill
You can see the most recent bill for any customer.


• Technologies Used in the Project 

1. Java
What is it? A powerful programming language used to build desktop, web, and mobile applications.

Why used here?

You used Java Swing to create the graphical user interface (GUI) – like buttons, forms, and windows that the user interacts with.
2. Java Swing

What is it? A part of Java that lets you build Windows-style apps with forms, buttons, text boxes, etc.

Why used here?

1. To create screens like:
2. Login page
3. Add customer form
4. Bill calculator
5. Generate bill view
