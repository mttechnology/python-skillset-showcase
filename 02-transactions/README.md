# 02 - Bank Transaction Processor

This Python notebook processes a series of banking transactions and performs two main tasks:

1. **Calculates the total amount per transaction type** (e.g., total deposits, total withdrawals, and total transfers).
2. **Computes the balance for each account** after applying all transactions.

---

## 💡 Features

- Categorizes transactions by type: `deposit`, `withdrawal`, and `transfer`
- Usses the .get() method to update transaction totals and account balances, even when the key doesn’t exist.
- Aggregates the total amount for each transaction type
- Computes the final balance for each account involved

## 🧾 Example Transactions

The transaction data is stored as a list of dictionaries:

```python
transactions = [
    {'trans_type': 'deposit', 'account': 'checking', 'amount': 5000},
    {'trans_type': 'withdrawal', 'account': 'checking', 'amount': 1200},
    {'trans_type': 'transfer', 'from_account': 'checking', 'to_account': 'savings', 'amount': 2000},
    {'trans_type': 'deposit', 'account': 'savings', 'amount': 3000},
    {'trans_type': 'withdrawal', 'account': 'savings', 'amount': 500},
    {'trans_type': 'transfer', 'from_account': 'savings', 'to_account': 'investment', 'amount': 1000},
]
