## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1 = eval(input())
dict2 = eval(input())
def merge():
    merged_dict = {**dict1, **dict2}
    print("Merged dictionary:", merged_dict)
merge()
```
## Output
![image](https://github.com/user-attachments/assets/93f9aa62-6d6b-47e9-a8a5-1d73c2a2fdf9)

## Result
Thus the given program is verified and executed sucessfully
