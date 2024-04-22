```python
# WITHOUT BASE CASE
def factorial(n):
    return n * factorial(n - 1)   # Incorrect! Missing base case

# WITH BASE CASE
def factorial(n):  # Correct! With base case
    if n == 0:
        return 1
    else:
        return n * factorial(n - 1)
```
