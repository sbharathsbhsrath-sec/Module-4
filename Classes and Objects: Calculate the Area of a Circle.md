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
    def mech(self, radius):
        area = math.pi * radius ** 2
        print("Area of the circle:", area)

radius = float(input("Enter the radius of the circle: "))
obj = cse()
obj.mech(radius)
```

## Output
<img width="1564" height="978" alt="image" src="https://github.com/user-attachments/assets/c5f7c4cd-3b15-43fc-9d60-1a8d4171c780" />

## Result
The program successfully calculates the area of a circle for any radius entered by the user using a class and method.
