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
dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 20, 'd': 4}
def merge():
    merged_dict = {**dict1, **dict2}  # dict2 values will overwrite dict1 if keys overlap
    return merged_dict
result = merge()
print("Merged dictionary:", result)

```

## Output
![image](https://github.com/user-attachments/assets/58e3756d-3916-4230-9f4b-ce832ef286df)


## Result
The code executed successfully.
