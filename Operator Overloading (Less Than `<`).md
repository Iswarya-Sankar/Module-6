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

```
class A:
    def __init__(self, a):
        self.a = a

    def __lt__(self, o):
        if self.a < o.a:
            return "ob1 is less than ob2"
        else:
            return "ob2 is less than ob1"


ob1 = A(10)
ob2 = A(20)

print(ob1 < ob2)
```
## Output

<img width="242" height="40" alt="601409327-041f8ba4-ae38-4a5c-b63f-8524aec240ab" src="https://github.com/user-attachments/assets/6f2d5119-c022-495c-b34a-71a41c355f45" />

## Result

Thus, the Python program to demonstrate operator overloading by overloading the less than (<) operator using a custom class was executed successfully and the output was verified.
