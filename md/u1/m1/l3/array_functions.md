```py
fruits = ["apple", "banana", "orange"]

fruits.append("mango")
# Now fruits = ["apple", "banana", "orange", "mango"]

fruits.insert(1, "kiwi")
# Now fruits = ["apple", "kiwi", "banana", "orange", "mango"]

fruits.remove("banana")
# Now fruits = ["apple", "kiwi", "orange", "mango"]

removed_item = fruits.pop(1)
# Now fruits = ["apple", "orange", "mango"]
# removed_item will be "kiwi"
```
