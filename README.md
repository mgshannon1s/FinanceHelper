# FinanceHelper
Personal finance helper to categorize transactions and track spending. 

API for Account Info: Plaid

Database: 
* PostGres Database Name:
 * Tables:
    * Transactions
    * Accounts

Features:
* Transaction Importer: Imports transactions from csv file (need to be careful of uniqueness) and also imports transactions from the Plaid api for future transactions. The csv file importer is necessary for historical transactions from Mint (the chase card that was set to inactive)
* Savings Tracker: Track how much goes to Savings/Investment vs how much is spent.
* Tax Expectations: Shows expected tax obligations

