```py
class Car:
  def __init__(self, make, model):
    self.__make = make  # Private attribute
    self.model = model  # Public attribute

  def get_make(self):  # Public method to access private make attribute
    return self.__make

  def accelerate(self):
    print(f"The {self.get_make()} {self.model} is accelerating!")
```
