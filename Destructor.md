# Destructor in Python

This project demonstrates how to implement a **destructor** in Python using a simple class.

## 🧠 Algorithm

1. Define a class named `vehicle`.
2. Inside the class, define the `__init__` method:
   - Initialize an print statement saying vehicle created.
3. Define the `__del__` method:
   - Print a message indicating the object is being destroyed.
4. Outside the class:
   - Create an instance of the `vehicle` class.
   - Delete the object using the `del` keyword.
## Program

class vehicle:
    
    def __init__(self):
        
        print("Vehicle created.")
        
    def __del__(self):
       
        print("Destructor called, vehicle deleted.")
 
obj=vehicle()  

del obj

## 🧪 Output

<img width="793" height="142" alt="image" src="https://github.com/user-attachments/assets/b6fd80b9-3d2f-4421-84e3-cb6d6c4c49bb" />


## Result
Thus the program is simulated sucessfully

