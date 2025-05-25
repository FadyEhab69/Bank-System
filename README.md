# Bank-System
This Entity-Relationship Diagram (ERD) represents a Bank System with the following entities and relationships :

BANK: Includes attributes like Name. A bank can have multiple BANK_ACCOUNTS (attached to relationship).
BANK_ACCOUNT: Contains attributes such as Balance, Bank, and Account_Owner. A bank account belongs to one BANK and is owned by one CLIENT. It can be attached to multiple TRANSACTIONS.
CLIENT: Has attributes like ClientID, First_name, and Last_name. A client can own multiple BANK_ACCOUNTS and perform multiple TRANSACTIONS.
TRANSACTION: Includes attributes like TransactionID, Money_amount, Deposit_account, Withdrawal_account, Currency, and Time. A transaction is attached to one BANK_ACCOUNT and performed by one CLIENT.
# Relationships:

A BANK has multiple BANK_ACCOUNTS (attached to).
A BANK_ACCOUNT belongs to one BANK.
A BANK_ACCOUNT is owned by one CLIENT.
A CLIENT owns multiple BANK_ACCOUNTS.
A CLIENT performs multiple TRANSACTIONS.
A BANK_ACCOUNT is attached to multiple TRANSACTIONS.
A TRANSACTION is performed by one CLIENT.
The ERD uses diamonds to represent relationships (e.g., "Belong_to," "Owned_by," "Attached_to," "Transaction") and ovals for attributes, with primary keys implied by the context (e.g., ClientID, TransactionID).
