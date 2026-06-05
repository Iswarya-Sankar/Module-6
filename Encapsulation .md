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

        print("Length:", self.__length)
        print("Breadth:", self.__breadth)


obj = Rectangle(10, 5)
```

## Output

<img width="233" height="66" alt="601408163-e2411005-d3a0-48fe-8754-895f2696eb67" src="https://github.com/user-attachments/assets/aaa3b3a4-068e-4a61-9eda-149703011932" />

## Result

Thus, the Python program to implement Encapsulation using private member variables __length and __breadth in the Rectangle class was executed successfully and the output was verified.
