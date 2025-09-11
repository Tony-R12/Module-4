# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
def sort_dict_by_value(input_dict):
    sorted_items = sorted(input_dict.items(), key=lambda item: item[1])
    return sorted_items
input_dict = {
    1: 2,
    5: 12,
    6: 18,
    4: 24,
    2: 56,
    3: 323
}
sorted_result = sort_dict_by_value(input_dict)
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_result)
```

## Sample Output
<img width="1130" height="192" alt="image" src="https://github.com/user-attachments/assets/1dc1ee43-9898-4a5f-aade-d711d6a1b952" />


## Result
Thus,a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order is created successfully.


