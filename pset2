# Credit card details.
balance = 484
annualInterestRate = 0.2
monthlyPaymentRate = 0.04


monthlyInterestRate = annualInterestRate / 12.0

# For each month.
for month in range(1, 13):
    # Compute the monthly payment.
    minPay = monthlyPaymentRate * balance

    # Update the outstanding balance.
    monUnpaidBalance = balance - minPay
    balance = (monUnpaidBalance * monthlyInterestRate) + monUnpaidBalance

# Print out the result statement with the total amount paid and the remaining balance.
print('Remaining balance: ' + str(round(balance, 2)))
