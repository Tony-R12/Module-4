# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(r):
        return math.pi*r*r
r=int(input())
obj=cse
print("Area of circle:",round(obj.mech(r),2))
```



## Output
<img width="648" height="205" alt="image" src="https://github.com/user-attachments/assets/95dda0b9-9cca-4e88-887e-b1ed199d3fcd" />

## Result
Thus,a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation is created successfully.




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
lst=[5, 10, 20]

try:
    
   print(lst[5])
except IndexError:
    print("You're out of list range")

```

## Output
<img width="626" height="167" alt="image" src="https://github.com/user-attachments/assets/5915e2f7-f19a-4693-aa73-0cd82d4884d8" />


## Result
Thus, a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list is created successfully.






# File Handling in Python: Count Lines Not Starting with 'T'

## 🎯 Aim
To write a Python program that counts the number of lines in a text file `story.txt` that do **not** start with the alphabet `'T'`.

## 🧠 Algorithm
1. Open the file `story.txt` in **read mode**.
2. Initialize a counter `count` to zero.
3. Iterate through each line of the file:
   - Check if the first character of the line is **not** `'T'`.
   - If the line does not start with `'T'`, increment the `count` by 1.
4. After processing all lines, print the `count` value, which represents the number of lines that do not start with `'T'`.

## 🧾 Program
```
def returnSum(myDict):
    final=0
    for i in myDict.values():
        final+=i
    return final
#driver functions

myDict = {'a': 100, 'b': 200, 'c': 300}
print("Sum :",returnSum(myDict))
```

## Output
<img width="395" height="167" alt="image" src="https://github.com/user-attachments/assets/b71b21ee-3710-4705-8054-015dfe7b17be" />



## Result
thus,the program is verified successfully.
