# Exp.No:5C
## Hierarchical Inheritance


### AIM  
To write a Python program to get the employee and doctor details and display them using hierarchical inheritance. Create a parent (base) class named `Details` and two child (derived) classes named `Employee` and `Doctor`.

### ALGORITHM

1. **Begin the program.**
2. **Create a class Details** with an `__init__` method to initialize three attributes: `id`, `name`, and `gender`.
3. **Define a method display_details()** to print the values of `id`, `name`, and `gender`.
4. **Create a class Employee** that inherits from the `Details` class. 
   - Add two additional attributes: `company` and `department`.
   - Override the `display_details()` method to print the employee-specific attributes (`company` and `department`) along with the inherited details.
5. **Create a class Doctor** that also inherits from the `Details` class. 
   - Add two additional attributes: `hospital` and `department`.
   - Override the `display_details()` method to print the doctor-specific attributes (`hospital` and `department`) along with the inherited details.
6. **Accept input** for employee and doctor details.
7. **Create objects of Employee and Doctor** using the input.
8. **Call the `display_details()` method** for both objects to print the details.
9. **Terminate the program.**


### PROGRAM
class A:     <br />
    def data(self): <br />
        self.idd = int(input())  <br />
        self.name = input() <br />
        self.gen = input()  <br />
        self.comp = input()  <br />
        self.dept = input() <br />
class B(A):   <br />
    def display1(self): <br />
        A.data(self)  <br />
        print("Employee Object") <br />
        print("Id: ",self.idd) <br />
        print("Name: ",self.name) <br />
        print("Gender: ",self.gen)     <br />
        print("Company: ",self.comp) <br />
        print("Department: ",self.dept) <br />
        print("") <br />
class C(B): <br />
    def display2(self): <br />
        A.data(self) <br />
        print("Doctor Object") <br />
        print("Id: ",self.idd) <br />
        print("Name: ",self.name) <br />
        print("Gender: ",self.gen) <br />
        print("Hospital: ",self.comp) <br />
        print("Department: ",self.dept) <br />
obj = C() <br /> 
objj = B()  <br />
objj.display1() <br />
obj.display2()

### OUTPUT  

![Screenshot 2025-05-01 123202](https://github.com/user-attachments/assets/949f8527-5b08-4430-9549-ff6267a6acbb)



### RESULT
Thus , the given pyhton program is implemented and executed sucessfully.
