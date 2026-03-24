# 🐍 Python OOP: Operator Overloading (Less Than `<`)

## 🎯 AIM

To write a Python program that demonstrates **operator overloading** by overloading the **less than (`<`)** operator using a custom class.

---

## 🧠 ALGORITHM

1. **Create Class `A`**:
   - Define the `__init__()` method to initialize the object with a value `a`.

2. **Overload the `<` Operator**:
   - Define the `__lt__()` method with logic:
     - If `self.a < o.a`, return `"ob1 is less than ob2"`
     - Else, return `"ob2 is less than ob1"`

3. **Create Objects**:
   - Instantiate two objects `ob1` and `ob2` with values.

4. **Use `<` Operator**:
   - Use `print(ob1 < ob2)` to trigger the overloaded behavior.

---

## 💻 Program

# Custom class
class Number:
    
    def __init__(self, value):
        self.value = value

    # Overload < operator
    def __lt__(self, other):
        return self.value < other.value

# Create objects
a = Number(10)
b = Number(20)

# Compare using <
if a < b:
    print("a is less than b")
else:
    print("a is not less than b")

## Output
<img width="1919" height="966" alt="image" src="https://github.com/user-attachments/assets/f322d3f7-a156-4259-ab7e-5b79e02517f9" />

## Result
