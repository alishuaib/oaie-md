```py
class Car:
  """A simple Car class."""
  def __init__(self, make, model):  # This is the constructor method
    self.make = make  # Attribute (data) for the car's make
    self.model = model  # Attribute (data) for the car's model

  def accelerate(self):
    """Simulates the car accelerating."""
    print(f"The {self.make} {self.model} is accelerating!")

  def brake(self):
    """Simulates the car braking."""
    print(f"The {self.make} {self.model} is braking!")
```
