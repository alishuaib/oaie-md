```python
apple = RestaurantItem("apple", 25, 0.75)  # Create an apple item
banana = RestaurantItem("banana", 10, 0.50) # Create a banana item

print(apple.name, apple.quantity)  # Output: apple 25
apple.update_quantity(30)           # Update apple quantity
print(apple.quantity)               # Output: 30
```
