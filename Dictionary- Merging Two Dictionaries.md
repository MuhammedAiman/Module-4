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
dict1 = {'a': 10, 'b': 20, 'c': 30}
dict2 = {'d': 40, 'e': 50, 'f': 60}

def merge(d1, d2):
    return {**d1, **d2}

result = merge(dict1, dict2)

print("Merged Dictionary:", result)
```
## Output

<img width="649" height="43" alt="601368790-cc1e0391-e741-4d42-bf36-4c6bc86fc675" src="https://github.com/user-attachments/assets/487475c0-03aa-471b-af97-7ba4e881cbe2" />

## Result

Thus, the Python program to merge two dictionaries and combine their key-value pairs was executed successfully and the output was verified.


