# ATM Management System (Console-Based)

## Overview
The **ATM Management System** is a console-based application developed using **Core Java**. It replicates essential functionalities of an ATM, allowing users to perform operations like login, balance inquiry, withdrawal, deposit, and viewing transaction history. This project leverages Object-Oriented Programming (OOP) principles to ensure modularity and code reusability.

## Features
- **Login System**: Secure user authentication with unique account credentials.
- **Check Balance**: View the current balance in the account.
- **Transaction History**: Retrieve a detailed statement of previous transactions.
- **Deposit Money**: Add funds to the account.
- **Withdraw Money**: Withdraw funds with validation for sufficient balance.
- **User-Friendly Interface**: Intuitive and easy-to-use text-based menu.

## Technologies Used
- **Programming Language**: Core Java
- **Concepts Used**: OOP principles (Inheritance, Polymorphism, Encapsulation)
- **Data Structures**: ArrayList, HashMap

## Getting Started
### Prerequisites
- Java Development Kit (JDK) version 8 or later
- IDE or text editor for Java (e.g., IntelliJ IDEA, Eclipse, or VS Code)

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/karimullashaikdev/Atm_Project.git
   ```
2. Navigate to the project directory:
   ```bash
   cd atm-management-system
   ```
3. Compile the Java files:
   ```bash
   javac src/*.java
   ```
4. Run the application:
   ```bash
   java src.Main
   ```

## Usage
1. Start the application.
2. Log in using your account credentials.
3. Choose an operation from the menu (e.g., check balance, withdraw, deposit).
4. Follow the prompts to complete the selected operation.
5. Log out when finished.

## Application Workflow
1. **Login**: Users authenticate using their account credentials.
2. **Perform Operations**: Users interact with options like balance inquiry, withdrawal, deposit, or viewing transaction history.
3. **Transaction Logging**: All operations are logged for review in the transaction history.
4. **Logout**: Users can safely exit after completing their tasks.

## Sample Output
```
Welcome to ATM Management System
---------------------------------
Enter Account Number: 12345
Enter PIN: ****

Login Successful!

Menu:
1. Check Balance
2. Withdraw Money
3. Deposit Money
4. View Statement
5. Logout

Enter your choice: 1

Your Current Balance: $5000

Enter your choice: 5
Thank you for using our ATM Management System!
```

## Project Structure
```
src/
├── Main.java             # Entry point of the application
├── Account.java          # Represents an account in the system
├── Transaction.java      # Logs transaction details
├── ATMOperations.java    # Handles core ATM functionalities
├── Authentication.java   # Manages user login and authentication
```

## Future Enhancements
- Adding multi-user support with a database integration.
- Implementing encryption for secure data storage.
- Introducing a graphical user interface (GUI) for a better user experience.
- Integrating with online banking systems for fund transfers.

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.

## Contact
For any queries or suggestions, feel free to reach out:
- **Name**: Karimulla Shaik
- **Email**: shaikkarimulladev@gmail.com
- **GitHub**: https://github.com/karimullashaikdev
