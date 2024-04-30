# Expense Tracker

## Overview
Expense Tracker is a Java application designed to help you manage your personal finances by tracking daily expenses.

## Prerequisites
- **Java JDK 11 or above**
- **JSON.simple library** for JSON processing (ensure it is included in your project's library)

## Building the Application
Follow these steps to build the application:

1. **Clone the repository:**
git clone [repository-url]

markdown
Copy code
2. **Navigate to the project directory:**
cd Expense_Tracker

csharp
Copy code

## Running the Application
You can run the application using either the GUI or the CLI as follows:

- **Run the GUI:**
java -jar ExpenseTracker.jar

markdown
Copy code
- **Use the CLI:**
java -cp ExpenseTracker.jar com.yourpackage.Main --cli

markdown
Copy code

## Using the Application

### Using the GUI
- **Add Expense:** Click on 'Add Expense' and fill in the details.
- **View Reports:** Navigate to the 'Reports' section to see your spending patterns.
- **Manage Categories:** Access the 'Settings' to modify expense categories.

### Using the CLI
- **Add an expense:**
java -cp ExpenseTracker.jar com.yourpackage.Main --add -amount 50 -category Food -date "2024-04-30"

markdown
Copy code
- **Generate a report:**
java -cp ExpenseTracker.jar com.yourpackage.Main --report

csharp
Copy code

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.