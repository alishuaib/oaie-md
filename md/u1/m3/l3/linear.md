```py
def linear_search(data, target):
  for index in range(len(data)):  # Look at each item
    if data[index] == target:
      return index  # Found it!
  return -1  # Didn't find the target
```
