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
```python
list1=[5, 10, 20] 

try: 

   print(list1[5]) 

except: 

   print("You're out of list range")
```

## Output

<img width="590" height="139" alt="530332441-9fe3fbe8-7f0b-486b-995f-63ba35418a91" src="https://github.com/user-attachments/assets/9e1e98ef-6bc1-4a84-a670-44b685932c45" />

## Result
Thus, the program has been successfully executed.
