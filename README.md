AURO_TECH ATM System
This is a simple ATM system in Python. Users can create accounts, log in, deposit money, withdraw money, transfer funds, and view their transaction history.

Features
Create a new account
Log in to an existing account
Deposit money
Withdraw money
Transfer money to another user
View transaction history
Log out
Requirements
Python 3.x
How to Run
Download the script:

bash
Copy code
git clone https://github.com/your-repository/atm-system.git
cd atm-system
Run the script:

bash
Copy code
python atm_system.py
Usage
Main Menu:

css
Copy code
Welcome to the AURO_TECH ATM....
1. Create a new account
2. Login
3. Quit
Enter your choice: 
Create a new account:

Select 1, then enter a user ID and PIN when prompted.
Login:

Select 2, then enter your user ID and PIN to log in.
ATM Menu:

After logging in, you'll see options to deposit, withdraw, transfer, view transaction history, or log out:
markdown
Copy code
ATM Menu:
1. Deposit
2. Withdraw
3. Transfer
4. View Transaction History
5. Logout
Enter your choice: 
Deposit:

Select 1, then enter the amount to deposit.
Withdraw:

Select 2, then enter the amount to withdraw.
Transfer:

Select 3, then enter the recipient's user ID and the amount to transfer.
View Transaction History:

Select 4 to see your transaction history.
Logout:

Select 5 to log out.
Quit:

From the main menu, select 3 to exit the program.
Example
yaml
Copy code
Welcome to the AURO_TECH ATM....
1. Create a new account
2. Login
3. Quit
Enter your choice: 1
Enter user ID: user123
Enter PIN: 1234
Account created.

Welcome to the AURO_TECH ATM....
1. Create a new account
2. Login
3. Quit
Enter your choice: 2
Enter user ID: user123
Enter PIN: 1234
Login successful.

ATM Menu:
1. Deposit
2. Withdraw
3. Transfer
4. View Transaction History
5. Logout
Enter your choice: 1
Enter deposit amount: 1000
ATM Menu:
1. Deposit
2. Withdraw
3. Transfer
4. View Transaction History
5. Logout
Enter your choice: 4
Transaction History:
Deposited Rs. 1000
License
This project is open-source and available under the MIT License.
