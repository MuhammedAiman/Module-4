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
class cse:
    def mech(self, r):
        area = 3.14 * r * r
        print("Area of Circle:", area)

radius = float(input("Enter radius: "))

obj = cse()
obj.mech(radius)

```
## Output

<img width="220" height="69" alt="601368497-f5ac3d14-78b4-4688-843e-3981e81a45f4" src="https://github.com/user-attachments/assets/7910c7fb-d5b5-411b-b0f9-4e65a0360fbb" />

## Result
Thus, the Python program to calculate the area of a circle using a class cse and method mech was executed successfully and the output was verified.
