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
        return area

radius = float(input("Enter the radius of the circle: "))
circle = cse()
area = circle.mech(radius)
print(f"Area of the circle with radius {radius} is: {area:.2f}")
```


## Output
![image](https://github.com/user-attachments/assets/a0247b2a-04cb-484c-9b10-94b7da2957e8)

## Result
Thus the program has been successfully executed
