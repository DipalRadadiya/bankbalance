# bankbalance
Implement a Python program that simulates a simple ATM. It should ask the user for their current balance and a withdrawal amount. If the withdrawal amount is greater than the balance, display an error message; otherwise, deduct the withdrawal amount from the balance and display the updated balance.
# Get the current balance from the user
current_balance = float(input("Enter your current balance: Rs."))

# Get the withdrawal amount from the user
withdrawal_amount = float(input("Enter the withdrawal amount: Rs."))

# Check if the withdrawal amount is greater than the balance
if withdrawal_amount > current_balance:
    print("Error: Insufficient funds. Withdrawal amount exceeds the current balance.")
else:
    # Deduct the withdrawal amount from the balance
    updated_balance = current_balance - withdrawal_amount
    print(f"Withdrawal successful! Updated balance: Rs.{updated_balance:.2f}")



Enter your current balance: Rs.1000
Enter the withdrawal amount: Rs.500
Withdrawal successful! Updated balance: Rs.500.00

Enter your current balance: Rs.500
Enter the withdrawal amount: Rs.700
Error: Insufficient funds. Withdrawal amount exceeds the current balance.
