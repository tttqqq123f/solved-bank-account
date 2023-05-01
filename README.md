Download Link: https://assignmentchef.com/product/solved-bank-account
<br>
STEP 1: Create the Multifile Project and the Main (Base) ClassCreate a new project that consists of the base class BankAccount.

The BankAccount class should contain, at minimum, the following members.

1.    It should contain data members to store a bank customer’s balance and account number. These should be of different and appropriate data types.

2.    It should have function members that do the following:

a.    set the account number;

b.    return the account number;

c.    return the account balance;

d.    deposit money into the account; and

e.    withdraw money from the account.

STEP 2: Create the CheckingAccount Class Derived From the BankAccount ClassThe class CheckingAccount should contain, at a minimum, the following members.

1.    It should contain a data member to keep track of the number of withdrawal transactions made on the account. Whenever a withdrawal is made, this number should be incremented.

2.    Override the base class, withdraw-money function, and add the capability to deduct transaction fees from an account using the following guidelines.

a.    The checking account is allowed three free transactions. For each successful withdrawal transaction past the three free transactions, there will be a service fee of 50 cents per transaction. The service fee should be deducted from the account balance at the time the transaction is made.

b.    If there are insufficient funds in the account balance to cover the withdrawal plus the service fee, the withdrawal should be denied.

c.    The function should return a value to indicate whether the transaction succeeded or failed. Transaction fees should be deducted only from successful transactions, but the transaction count should be incremented in either case.

STEP 3: Test Program Operation

1.    All data-input and data-display operations (cin and cout) should be done in the function main() test program.

2.    The test program should create one checking account and one savings account with initial balances of $100 each using the functions defined in the class definitions. The test program should also assign a unique, five-digit account number to each account and assign an annual interest rate of 3% for the savings account.

3.    The test program should then display a menu that allows the user to select which option is to be performed on which account, including the following.

a.    Make a deposit and specify the amount to a selected or an entered account.

b.    Make a withdrawal and specify the amount to a selected or an entered account.

c.    Return the balance of a selected or an entered account.

i.        For deposit transactions, withdrawal transactions, and balance inquiries, the updated balance and any fees charged or interest earned should also be displayed.

ii.        For the savings account, the number of days since last transaction should be displayed.

d.    Exit the program.

4.    Each account operation should display the account number and the account type.