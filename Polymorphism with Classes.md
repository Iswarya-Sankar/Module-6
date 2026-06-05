# # 🐍 Python OOP: Polymorphism with Classes

## 🎯 AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.

---

## 🧠 ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.

---

## 💻 Program

```
class Beans:
    def type(self):
        print("Vegetable")

    def color(self):
        print("Green")


class Mango:
    def type(self):
        print("Fruit")

    def color(self):
        print("Yellow")


def func(obj):
    obj.type()
    obj.color()


b = Beans()
m = Mango()

func(b)
func(m)
```
## Output

<img width="198" height="111" alt="601409866-c3038dd0-11e3-4330-8496-668b192a8279" src="https://github.com/user-attachments/assets/09b44e32-cc4f-4b25-bc8b-96c80a9aee65" />

## Result
Thus, the Python program to demonstrate polymorphism using the classes Beans and Mango with a generic function was executed successfully and the output was verified.
