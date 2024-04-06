```py
import os

if os.path.exists("old_data.txt"):  # Check if file exists (optional)
  os.remove("old_data.txt")
  print("File deleted successfully!")
else:
  print("File 'old_data.txt' not found.")
```
