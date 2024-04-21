```python
class RestaurantItem:
    def __init__(self, name, quantity, price):
        self.name = name
        self.quantity = quantity
        self.price = price

    def update_quantity(self, new_quantity):
        self.quantity = new_quantity

class Inventory:
    def __init__(self):
        self.inventory = []

    def add_inventory_item(name, quantity, price):
        new_item = RestaurantItem(name, quantity, price)
        self.inventory.append(new_item)

    def update_inventory_quantity(name, new_quantity):
        for item in self.inventory:
            if item.name == name:
                item.update_quantity(new_quantity)
                return  # Found and updated
        print("Item not found")  # Item wasn't in the inventory

    def remove_inventory_item(name):
        for i in range(len(self.inventory)):
            if self.inventory[i].name == name:
                del self.inventory[i]  # Remove the item
                return
        print("Item not found")
```
