```py
file = open("data.txt", "r")
lines = file.readlines()  # Read all lines into a list
lines[1] = "This line is updated!\n"  # Modify a specific line
file = open("data.txt", "w")  # Open in write mode (overwrites)
file.writelines(lines)  # Write the modified list back to the file
file.close()
```
