# Exp.No:20  
## SEB - Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError.

### AIM  
To handle a ZeroDivisionError in Python using a try-except block and display a message: "You can't divide with 0" when an attempt is made to divide by zero.

### ALGORITHM

1.Start.

2.Input two integers a and b from the user.

3.Try to divide a by b (i.e., c = a / b).

4.If division is successful, print the result c.

5.If b is zero, catch the ZeroDivisionError.

6.Display the message "You can't divide with 0" in case of a ZeroDivisionError.


### PROGRAM
# REG NO:212223090008
# NAME:Harinishri S
```
a=int(input())
b=int(input())
try:
    c=a/b
    print(c)
except ZeroDivisionError:
    print("You can't divide with 0")



```

### OUTPUT

![errorhandling](https://github.com/user-attachments/assets/d3a72ff5-b640-4b56-8de2-f31aabd19257)




### RESULT
This represents how the program behaves based on different inputs, handling both valid and invalid division scenarios effectively.









