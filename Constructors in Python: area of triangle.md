# # Constructors in Python: area of triangle

## 🎯 Aim
Write python code to create a class Triangle and initialiaze the attributes(base and height) using default constructor and calculate the area of the triangle using user defined function.

## 🧠 Algorithm
1. **Define the class**: Create a class `triangle` with a default constructor (`__init__`).
2. **Default Constructor**: In the constructor, assign the user input (base,height) to an instance variable `self.base and self.height`.
3. **Display Message**: Define a method `view` that prints "area of triangle".
4. **Execute the Program**: Instantiate the `triangle` class and call the `view` method.

## 🧾 Program

class triangle:
    
    def __init__(self,base,height):
    
        self.base=base
        
        self.height=height
    
    def view(self):
    
        print(f"Area of triangle: {0.5*self.base*self.height}")
        
a=int(input())

b=int(input())

t=triangle(a,b)

t.view()

## Output

<img width="658" height="272" alt="image" src="https://github.com/user-attachments/assets/dd8b355c-3b31-4034-8590-66573cbffb54" />


## Result
Thus the program is simulated sucessfully
