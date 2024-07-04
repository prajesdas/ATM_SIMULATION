# ATM_SIMULATION
ATM Machine Simulation with Pywebio and Flask 🚀💳
Welcome to the ATM Machine Simulation project! This application demonstrates a simple ATM machine system implemented using Python. It includes core functionalities such as balance inquiry, cash withdrawal, cash deposit, PIN change, and transaction history. Additionally, the project uses the Flask framework to create a web interface, enhanced by Pywebio for interactive input and output.

Features ✨
Balance Inquiry: Check your current account balance.
Cash Withdrawal: Withdraw cash if sufficient balance is available.
Cash Deposit: Deposit cash into your account.
PIN Change: Change your account PIN.
Transaction History: View the history of all transactions.
Running the Application 🚀
To start the application, run the following command:

bash
Copy code
python app.py
The application will be accessible at http://localhost:8080.

Usage 🖥️
Open your browser and navigate to http://localhost:8080.
Insert your card (simulate by pressing Enter).
Enter your PIN to authenticate.
Choose an action from the menu:
Balance Inquiry
Cash Withdrawal
Cash Deposit
Change PIN
Transaction History
Follow the prompts to complete your selected action.
Code Overview 📚
ATMMachine Class
Attributes:
pin: The PIN for authentication.
balance: The account balance.
transaction_history: List of all transactions.
Methods:
check_pin(pin): Verifies if the entered PIN is correct.
balance_inquiry(): Returns the current balance.
cash_withdrawal(amount): Withdraws the specified amount if sufficient balance is available.
cash_deposit(amount): Deposits the specified amount.
change_pin(old_pin, new_pin): Changes the PIN if the old PIN is correct.
get_transaction_history(): Returns the transaction history.
Flask Application
Routes:
/: Home page.
/atm: ATM operations interface.
Pywebio Integration
Functions:
check_pin(): Handles PIN checking.
balance_inquiry(): Handles balance inquiry.
cash_withdrawal(): Handles cash withdrawal.
cash_deposit(): Handles cash deposit.
change_pin(): Handles PIN change.
transaction_history(): Handles transaction history retrieval.
Contributing 🤝
Contributions are welcome! Feel free to submit issues, fork the repository, and open pull requests.

License 📄
This project is licensed under the MIT License. See the LICENSE file for details.

Acknowledgements 🙏
Inspired by real-world ATM systems.
Developed using Flask and Pywebio.
Enjoy using the ATM Machine Simulation! 💸

Feel free to reach out if you have any questions or suggestions. 😊
