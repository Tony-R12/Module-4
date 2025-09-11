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
dict1 =eval(input())


dict2 =eval(input())

# Merge the dictionaries
merged_dict = {**dict2, **dict1}

# Print the merged dictionary
print(merged_dict)
```


## Output
<img width="1126" height="242" alt="image" src="https://github.com/user-attachments/assets/3949133d-abd1-4338-9a9e-5f7b1adc57ba" />


## Result
Thus, a Python program that merges **two dictionaries** and combines their key-value pairs is created successfully.
