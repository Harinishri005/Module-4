# Exp.No:19  
## CLASS AND OBJECTS - AREA OF CIRCLE


### AIM  
To write Python Program to take the radius from the user and find the area of the circle using class name 'pen' and function name 'stationary'

### ALGORITHM

1.Start the program.

2.Define a class called pen.

3.Inside the class, define a method named stationary.

4.In the stationary method, prompt the user to enter the radius of the circle.

5.Convert the user input to a floating-point number.

6.Use the formula area = π * radius² to calculate the area.

7.Display the area to the user.

8.Create an object of the class pen.

9.Call the stationary method using the object.

10.End the program.



### PROGRAM
### REG NO:212223090008
### NAME:Harinishri S

```
import math
class circle:
    def area(r):
        return math.pi*r*r
r=int(input())
obj=circle
print("Area of circle:",round(obj.area(r),2))



```

### OUTPUT


![m4-1res](https://github.com/user-attachments/assets/085d03e3-83fd-42d4-9377-50979625f907)



### RESULT
The program successfully calculates the area of a circle using the user-provided radius by applying the formula area = π * r².



