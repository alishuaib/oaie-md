```python
import timeit

inventory = load_inventory()  # Assume you have an inventory loaded

def bubble_sort(inventory):
    # ... Bubble sort implementation ...

def merge_sort(inventory):
    # ... Merge sort implementation ...

# Time Bubble Sort
setup_code = "from __main__ import bubble_sort, inventory"
time_taken = timeit.timeit(setup=setup_code, stmt="bubble_sort(inventory.copy())", number=1000)
print("Time taken for bubble sort:", time_taken, "seconds")

# Time Merge Sort
setup_code = "from __main__ import merge_sort, inventory"
time_taken = timeit.timeit(setup=setup_code, stmt="merge_sort(inventory.copy())", number=1000)
print("Time taken for merge sort:", time_taken, "seconds")
```
