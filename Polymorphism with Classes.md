# #  Python OOP: Polymorphism with Classes

##  AIM

To create two specific classes — `Beans` and `Mango`. Then, create a **generic function** that can accept any object and determine its **type** (Fruit or Vegetable) and **color**, using polymorphism.



##  ALGORITHM

1. **Create Class `Beans`**:
   - Define `type()` method that prints `"Vegetable"`.
   - Define `color()` method that prints `"Green"`.

2. **Create Class `Mango`**:
   - Define `type()` method that prints `"Fruit"`.
   - Define `color()` method that prints `"Yellow"`.

3. **Define Generic Function `func(obj)`**:
   - Call `obj.type()` and `obj.color()` — this works with both `Beans` and `Mango` objects, showcasing **polymorphism**.

4. **Create Objects**:
   - Instantiate `Beans` and `Mango`.
   - Pass them to `func()` and execute the program.



##Program
```
class Beans(): 
     def type(self): 
       print("Vegetable") 
     def color(self):
       print("Green") 
class Mango(): 
     def type(self): 
       print("Fruit") 
     def color(self): 
       print("Yellow")
obj_beans = Beans() 
obj_mango = Mango()
for func in (obj_beans,obj_mango): 
    func.type()
    func.color()
```
## Output
<img width="1181" height="342" alt="544863986-056467dd-5524-4e4d-9e9f-677613d52cf9" src="https://github.com/user-attachments/assets/aa53a1b5-6d9a-4793-9b1b-b6307869f3bb" />

## Result
Thus,the program is executed successfully.
