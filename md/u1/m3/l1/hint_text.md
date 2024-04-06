```py
def register_user():
  name = input("Enter your name: ")
  email = input("Enter your email: ")
  data = f"{name},{email}\n"  # Combine with comma and newline

  # Open in append mode to add new entries
  with open("users.txt", "a") as file:
    file.write(data)
  print("Registration successful!")

# Run the registration function
register_user()
```
