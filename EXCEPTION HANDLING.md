# Exp.No:17  
## EXCEPTION HANDLING

### AIM  
To handle IndexError in Python using a try-except block and display a message: "You're out of list range" when an invalid index is accessed.


### ALGORITHM

1.Define a custom exception class IndexError that inherits from Exception.

2.Inside the class, define a method msg() to print "You're out of list range".

3.Create a list lst with elements [5, 10, 20].

4.Try to access an invalid index lst[5] to raise an IndexError.

5.Catch the IndexError exception and instantiate the custom exception.

6.Call the msg() method of the custom exception class to display the message.



### PROGRAM
# Reg.No:212223090008
# Name:Harinishri S
```
class IndexError(Exception):
    def msg(self):
        print("You're out of list range")
lst=[5, 10, 20]
try:
    raise IndexError
    print(lst[5])
except IndexError:
    b=IndexError()
b.msg()

```

### OUTPUT

![exception](https://github.com/user-attachments/assets/0cc53627-6b33-4b98-a52a-2a7b34dfc874)



### RESULT
This provides a clean way to handle index errors using a custom exception class.
