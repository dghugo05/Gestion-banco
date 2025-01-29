# README for Banking Management System
## Overview
This project is a simple Banking Management System implemented in Java, allowing users to create and manage different types of bank accounts. It provides functionalities such as account creation, deposits, withdrawals, balance inquiries, and interest calculations. The application uses an interactive console-based menu for user engagement.

## Features
· Create Accounts: Users can create either a Savings Account or a Current Account based on their requirements.  
· Deposit Money: Funds can be deposited into existing accounts.  
· Withdraw Money: Users can withdraw funds, subject to account balance.  
· Check Balance: Users can view the current balance of their accounts.  
· Calculate Interest: The system allows for automatic calculation and addition of interest based on the type of account.  
· User-friendly Interface: The application features a simple menu system for navigation.  

## Project Structure
The project contains the following classes:

1. Banco.java: The main class that drives the program and presents the user menu.  
2. GestionBanco.java: This class handles the operations related to managing bank accounts, such as creating accounts and executing transactions.  
3. CuentaBancaria.java: An abstract class that serves as a blueprint for different types of bank accounts, implementing basic operations like deposit, withdrawal, and interest calculation.  
4. CuentaCorriente.java: A class representing a Current Account, extending the functionality of the CuentaBancaria class.  
5. CuentaAhorro.java: A class representing a Savings Account, also extending the CuentaBancaria class.  
6. Operaciones.java: An interface defining the operations (like calculating interest and displaying balance) that must be implemented by any bank account.  

## Getting Started
To run this project, ensure you have Java installed on your system. After cloning the repository, compile the Java files and start the application by running the main class, which will present you with a menu for interaction. Follow the on-screen instructions to create accounts and perform banking operations. The system facilitates entering details needed for transactions such as the account holder's name and amounts for deposits or withdrawals. When you want to exit the application, you can simply choose the exit option from the main menu.

## Contributing
If you wish to contribute to this project, feel free to fork the repository and submit a pull request. For enhancements or bug reports, please create an issue on the project repository.
