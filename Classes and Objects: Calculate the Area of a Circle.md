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
