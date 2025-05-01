# Exp.No:5E
## Multiple Inheritance



### AIM  
To write a Python program to get the name, attendance, and ID of a student and check if they are eligible for the next module using multiple inheritance. If attendance > 80, the student is eligible; otherwise, not eligible.



### ALGORITHM

1. Define the `Student` class.
2. Inside the `Student` class, define the `__init__` method (constructor). The `__init__` method accepts two parameters: `name` and `student_id`.
    - Inside the `__init__` method: Assign the value of `name` to `self.name` and `student_id` to `self.student_id`.
3. Define the `get_student_info` method inside the `Student` class:
    - This method should return a string formatted with `self.name` and `self.student_id`.
4. Define the `Attendance` class, which inherits from the `Student` class.
5. Inside the `Attendance` class, define the `__init__` method (constructor).
    - The `__init__` method accepts three parameters: `name`, `student_id`, and `attendance`.
    - Inside the `__init__` method: Call the parent class constructor `super().__init__(name, student_id)` to initialize `name` and `student_id`. Assign the value of `attendance` to `self.attendance`.
6. Define the `check_eligibility` method inside the `Attendance` class:
    - If `self.attendance` is greater than 80, return a formatted string indicating the student is eligible for the module exam.
    - Otherwise, return a formatted string indicating the student is not eligible for the module exam.
7. Prompt the user to enter the `name` (as a string), `student_id` (as an integer), and `attendance` (as an integer).
8. Create an instance `student` of the `Attendance` class, passing the entered `name`, `student_id`, and `attendance` to the constructor.
9. Call the `check_eligibility` method on the `student` object and print the result.
10. Terminate the program.


### PROGRAM

class A:     <br />
    def get(self):   <br />
        self.a = input()   <br />
        self.b = int(input()) <br />
        self.c = int(input())  <br />
class B:     <br />
    def check(self): <br />
        if self.c > 90: <br />
            print("Eligible for Placement") <br />
        else:    <br />
            print("Not Eligible for Placement")     <br />
class C(A,B):     <br />
    def display(self):   <br />
        A.get(self)  <br />
        print(self.a) <br />
        print(self.b)    <br />
        B.check(self)   <br />
ob = C() <br />
ob.display()

### OUTPUT

![Screenshot 2025-05-01 124008](https://github.com/user-attachments/assets/41a79ebb-b245-4568-a749-8527f6e2fddc)

### RESULT
 Thus , the given python program is implemented and executed sucessfully.



