# Exp.No:5B
## Destructor


### AIM  
To create a Python class `vehicle` with a destructor.


### ALGORITHM

1. Begin the program.  
2. Define the `vehicle` class.  
3. Inside the `vehicle` class, define the `__init__` method (constructor) and the `__del__` method (destructor).  
4. Create an object `s2` of the `vehicle` class. When the object `s2` is created, the `__init__` method is called, and its print statements are executed.  
5. Use the `del` statement to delete the object `s2`. This triggers the `__del__` method (destructor), and the respective print statements are executed.  
6. Terminate the program.



### PROGRAM
class Vehicles:   <br />
    def __init__(self):    <br />
        print('Vehicle created.')    <br />
    def __del__(self):     <br />
        print("Destructor called, vehicle deleted.")     <br />
obj = Fruits()         <br />
del obj


### OUTPUT

![Screenshot 2025-05-01 122549](https://github.com/user-attachments/assets/7cfd4c07-8dc1-40d3-9a91-005aacdfe9ea)

### RESULT
Thus, the given python progran is implemented and executed sucessfully.
