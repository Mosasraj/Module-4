# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
try:
    a=eval(input())
    print(a[4])
except:
    print("check index range")
```
## Output
![image](https://github.com/user-attachments/assets/4594245a-4ef2-409e-8653-0799fd37a77b)

## Result
Thus the given program is verified and executed sucessfully
