```py
import pandas as pd

# Create a sample DataFrame
data = {'Product': ['Shirt', 'Hat', 'Shoes'], 'Price': [20, 15, 50]}
sales_data = pd.DataFrame(data)

# Find the most expensive product
most_expensive = sales_data[sales_data['Price'] == sales_data['Price'].max()]

print(f"Most expensive product: {most_expensive}")
```
