```py
class Car:
  def __init__(self, make, model):
    self.make = make
    self.model = model

  def accelerate(self):
    print(f"The car is accelerating!")

class SportsCar(Car):
  def __init__(self, make, model, horsepower):
    super().__init__(make, model)  # Call base class constructor
    self.horsepower = horsepower

  def accelerate(self):  # Override the accelerate method
    print(f"The {self.make} {self.model} with {self.horsepower} hp is zooming ahead!")
```
