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
data = {2: 56, 1: 2, 5: 12, 4: 24, 6: 18, 3: 323}
print("Original Dictionary:")
print(data)
sorted_by_keys = dict(sorted(data.items()))
print("\nDictionary Sorted by Keys:")
print(sorted_by_keys)
sorted_by_values = dict(sorted(data.items(), key=lambda item: item[1]))
print("\nDictionary Sorted by Values:")
print(sorted_by_values)
```
# End the program
## Sample Output
![image](https://github.com/user-attachments/assets/3cbcefdf-96f9-4966-a008-8d8b1898121f)
## Result
Thus the given program is verified and executed sucessfully
