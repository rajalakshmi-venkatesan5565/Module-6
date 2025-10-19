# 🐍 Python OOP: Encapsulation with Private Members

## 🎯 AIM

To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth`.

---

## 🧠 ALGORITHM

1. **Define the Class**:
   - Create a class `Rectangle` with two private attributes: `__length` and `__breadth`.

2. **Initialize Variables**:
   - Use the `__init__()` constructor to set initial values for `__length` and `__breadth`.

3. **Print Values**:
   - Display the private variables from within the class to demonstrate access.

4. **Instantiate the Object**:
   - Create an object of the `Rectangle` class to trigger the constructor.

---

## 💻 Program
```
class Rectangle:
    
    def __init__(self, length, breadth):
        self.__length = length      
        self.__breadth = breadth    
        self.display_dimensions()  

    
    def display_dimensions(self):
        print(f"Length: {self.__length}")
        print(f"Breadth: {self.__breadth}")


rect = Rectangle(10, 5)
```
## Output
<img width="920" height="288" alt="Screenshot 2025-10-19 125133" src="https://github.com/user-attachments/assets/ff605841-8a86-48ff-81dc-573e7a2cf7d0" />

## Result
To implement **Encapsulation** in Python by defining a class `Rectangle` with **private member variables** `__length` and `__breadth` is executed successfully.
