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

class Rectangle:
    
    def __init__(self, length, breadth):
        self.__length = length      # private variable
        self.__breadth = breadth    # private variable

    # Getter methods
    def get_length(self):
        return self.__length

    def get_breadth(self):
        return self.__breadth

    # Setter methods
    def set_length(self, length):
        self.__length = length

    def set_breadth(self, breadth):
        self.__breadth = breadth

    # Method to calculate area
    def area(self):
        return self.__length * self.__breadth


# Create object
rect = Rectangle(5, 3)

# Access using methods
print("Length:", rect.get_length())
print("Breadth:", rect.get_breadth())

# Modify values
rect.set_length(10)
rect.set_breadth(4)

print("Updated Area:", rect.area())

## Output
<img width="1919" height="960" alt="image" src="https://github.com/user-attachments/assets/40d4cc7e-6543-4afe-8ba4-df105c12cfa5" />

## Result
