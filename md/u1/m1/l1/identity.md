```py
number1 = 10
number2 = 10
number3 = number1  # number3 is same as number1
number4 = 20

# Output: True (both refer to the same integer object)
print(number1 is number2)
# Output: True (number3 points to the same object as number1)
print(number1 is number3)
# Output: False (number4 is not same as number1)
print(number1 is number4)
```
