* The commission for the month --> output
* Sales of the month ($) and commission rate (%) --> input
* How? CommissionEarned = SalesAmount * (CommissionRate/100)


# Pseudocode
## Main Module

Declare SalesAmount as a Float

Declare CommissionRate as a Float

Write "Commission Rate Program"

Write

Write "This program computes a salesperson's monthly earned commission amount"

Write "in dollars."

Call Input Data Module

Call Process Data Module

Call Output Results Module

End program


## Input Data Module

Write "Please enter your sales for the month in dollars."

Input SalesAmount

Write "Enter your commission rate as a percentage."

Input CommissionRate


## Process Data Module

Declare CommissionEarned as a Float

CommissionEarned = SalesAmount*(CommissionRate/100)

## Output Results Module

Write "Your commission total for the month is " + CommissionEarned
