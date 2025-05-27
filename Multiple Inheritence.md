# Arithmetic Operations Using Multiple Inheritance in Python

This Python program demonstrates **multiple inheritance** by performing basic arithmetic operations — Addition, Subtraction, and Division — using three classes.

## 🎯 Aim

To write a Python program to calculate **Add, Sub & Division** using **Multiple Inheritance**.

## 🧠 Algorithm

1. **Define `Calculation1` class**
   - Contains `Summation(a, b)` method to return the sum of two numbers.
2. **Define `Calculation2` class**
   - Contains `Subtraction(a, b)` method to return the difference of two numbers.
3. **Define `Derived` class**
   - Inherits from both `Calculation1` and `Calculation2`.
   - Contains `Division(a, b)` method to return the division result.
4. **Input**
   - Prompt the user to enter two numbers.
5. **Process**
   - Create an object of the `Derived` class.
   - Call `Summation`, `Subtraction`, and `Division` methods.
6. **Output**
   - Display the results of the three operations.

## 💻 Program 
Add code here
```
  class Calculation1:  
      def Summation(self,a,b):  
          return a+b  
  class Calculation2:  
      def sub(self,a,b):  
          return a-b  
  class Derived(Calculation1,Calculation2):  
      def Mul(self,a,b): 
          return a*b
          
  a=int(input())
  b=int(input())
  
  d = Derived()  
  print(d.Summation(a,b))  
  print(d.sub(a,b))  
  print(d.Mul(a,b))
```
## Output Example
![image](https://github.com/user-attachments/assets/a99b4294-7baa-4e21-9d89-5701ae8d68c4)

Result
Thus, the program has been execueted successfully
