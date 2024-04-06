```py
file = open("data.txt", "r")
for line in file:
  print(line, end="")  # Print each line without a newline at the end
file.close()
```
