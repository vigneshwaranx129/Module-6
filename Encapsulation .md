# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM
## 💻 Program
```
class Rectangle:
    def __init__(self, length, width):
        self.__length = length  # Private variable
        self.__width = width    # Private variable
    
    def print_values(self):
        print(self.__length)
        print(self.__width)

rect = Rectangle(5, 3)
rect.print_values()
```
## Output
<img width="1172" height="274" alt="image" src="https://github.com/user-attachments/assets/e9e44b6d-b1ae-474b-bff0-a401a83a4145" />
## Result
Thus, the program is executed successfully.
