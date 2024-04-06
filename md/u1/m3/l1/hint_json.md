```py
import json

def calculate_total_price():
  total_price = 0
  with open("products.json", "r") as json_file:
    products = json.load(json_file)  # Load JSON data as a list
  for product in products:
    total_price += product["price"]
  return total_price

total = calculate_total_price()
print(f"Total price for all products: ${total:.2f}")
```
