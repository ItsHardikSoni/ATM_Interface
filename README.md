# ATM Interface in Java

A simple ATM simulation developed using Java and object-oriented programming concepts. The application allows users to perform basic banking operations through a menu-driven console interface.

## Features

- Check Balance: Display the current account balance.
- Deposit: Add money to the bank account.
- Withdraw: Withdraw money when sufficient balance is available.
- Input Validation: Reject invalid deposit and withdrawal amounts.
- Insufficient Balance Check: Prevent withdrawals exceeding the available balance.
- Menu-driven Interface: Navigate through banking operations.

## Technologies Used

- Java
- Object-Oriented Programming (OOP)
- Classes and Objects
- Constructors
- Encapsulation
- Scanner Class

## Project Structure

\`\`\`text
ATM_Interface/
├── src/
│   ├── Main.java
│   ├── ATM.java
│   └── BankAccount.java
└── README.md
\`\`\`

## How to Run

1. Clone the repository:

   \`\`\`bash
   git clone https://github.com/ItsHardikSoni/ATM_Interface.git
   \`\`\`

2. Navigate to the project:

   \`\`\`bash
   cd ATM_Interface
   \`\`\`

3. Compile the Java files:

   \`\`\`bash
   javac -d out src/*.java
   \`\`\`

4. Run the application:

   \`\`\`bash
   java -cp out Main
   \`\`\`

## Application Workflow

1. Create a bank account with an initial balance.
2. Display the ATM menu.
3. Select an operation.
4. Perform the selected banking operation.
5. Continue until the user exits.

## Learning Outcomes

- Applying OOP principles in Java.
- Working with multiple classes.
- Understanding constructors and object initialization.
- Implementing basic banking operations.
- Applying validation to financial inputs.

## Note

This is an educational console-based simulation. It is not connected to a real banking system and does not implement production-grade authentication or transaction processing.

## Author

**Ayush**

[GitHub](https://github.com/ItsHardikSoni)
