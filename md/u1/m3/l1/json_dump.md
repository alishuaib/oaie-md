```py
# Sample Python data (dictionary)
user_data = {
  "username": "johndoe123",
  "email": "john.doe@example.com"
}

# Open the file (assuming "user.json" will be created)
with open("user.json", "w") as json_file:
  # Dump the Python data as a JSON string to the file
  json.dump(user_data, json_file, indent=4)  # Optional: indent for readability
```
