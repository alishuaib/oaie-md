```py
import json

# Open the file (assuming "data.json" exists)
with open("data.json", "r") as json_file:
  # Load the JSON data into a Python dictionary
  data = json.load(json_file)

# Access data using dictionary keys
name = data["name"]
items = data["items"]
print(f"Hello, {name}! Here's your shopping list:")
for item in items:
  print(item)
```
