```py
import unittest

def add(x, y):
    return x + y

class TestCalculator(unittest.TestCase):
    def test_two_positive(self):
        self.assertEqual(add(2, 3), 5)

    def test_positive_and_negative(self):
        self.assertEqual(add(-5, 8), 3)

if __name__ == '__main__':
    unittest.main()
```
