# atm_application
ATM Interface Application

Creating a Java program that implements an ATM machine with the specified features. The program includes an ATM class, a BankAccount class, and methods for withdrawing, depositing, and checking the balance. It also validates user input and displays appropriate messages.       
1-BankAccount Class: Represents a user's bank account, allowing for deposits, withdrawals, and balance checks. It includes validation to ensure deposits are positive and withdrawals do not exceed the available balance.       
2-ATM Class: Represents the ATM interface, providing methods to display a menu, withdraw money, deposit money, and check the account balance. It interacts with the BankAccount class to perform transactions.     
3-ATMApplication Class: The main class that initializes a BankAccount with a preset balance (e.g., $1000) and creates an ATM instance. It presents a text-based menu to the user, allowing them to perform transactions until they choose to exit.    
4-User Input Validation: The program ensures that withdrawal amounts do not exceed the balance and that deposit amounts are positive, while also handling invalid menu selections.   
Overall, the program provides a simple, interactive ATM experience through a console interface, allowing users to manage their bank account effectively.
