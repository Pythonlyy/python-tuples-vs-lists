# ⚖️ Tuples vs. Lists in Python

Understand the key differences between tuples and lists — and when to use which.

---

## 💡 What You'll Learn

* The difference between tuples and lists
* When to use a tuple vs. a list
* How immutability affects your code

---

## 💻 Example with Explanation

### 📋 Create a list and a tuple:

```python
my_list = ["Alice", 31, "Berlin"]
my_tuple = ("Alice", 31, "Berlin")
```

### ✏️ Lists can be changed:

```python
my_list = ["Alice", 31, "Berlin"]
my_list[1] = 32
print(my_list)
```

🖨️ Output:

```
['Alice', 32, 'Berlin']
```

### 🚫 Tuples cannot be changed:

```python
my_tuple = ("Alice", 31, "Berlin")
my_tuple[1] = 32  # ❌ Error
```

🖨️ Output:

```
TypeError: 'tuple' object does not support item assignment
```

---

## 📌 Key Notes

* Use **lists** when data may change (e.g., todo items, inputs)
* Use **tuples** when data is fixed (e.g., coordinates, config, roles)
* Tuples are slightly faster and more memory-efficient

---

## 🧪 Try It Yourself

```python
colors_list = ["red", "green", "blue"]
colors_tuple = ("red", "green", "blue")

print("List:", colors_list)
print("Tuple:", colors_tuple)
```

### 🔈 Expected Output

```
List: ['red', 'green', 'blue']
Tuple: ('red', 'green', 'blue')
```

---

💡 **Quick Tip:** Use tuples for safe, constant data — like days of the week:

```python
days = ("Mon", "Tue", "Wed", "Thu", "Fri", "Sat", "Sun")
print("Weekend starts on:", days[5])
```

🖨️ Output:

```
Weekend starts on: Sat
```

---

🐍 This is part of the **Pythonly** beginner series.
Learn Python one line at a time. Follow **[@Pythonly](https://www.youtube.com/@Pythonly)** for more.

---

