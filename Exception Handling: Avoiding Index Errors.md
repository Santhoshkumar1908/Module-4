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
try:
    # Taking 3 elements input from the user
    L = []
    for i in range(3):
        item = ['laptop','mobile','pen']
        L.append(item)

    # Trying to access index 4
    print(L[4])

except IndexError:
    print("check index range")


## Output
<img width="1150" height="332" alt="Screenshot 2025-10-22 160424" src="https://github.com/user-attachments/assets/0dacb6dd-b426-48aa-ab27-0c88e66f1702" />


## Result
thus the program runs successfully
