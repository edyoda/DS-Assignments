# OOP Assignment

## Challenge 1: Square Numbers and Return Their Sum

In this challenge, you need to implement a method that squares passing variables and returns their sum.

**Problem statement**:
Implement a class `Point` that has three properties and a method. All these attributes (properties and methods) should be `public`. This problem can be broken down into two tasks:

*Task 1*:
👉 Implement a constructor to initialize the values of three properties: x, y, and z.

*Task 2*:
👉 Implement a method, `sqSum()`, in the `Point` class which squares `x`, `y`, and `z` and returns their sum.

Sample properties
    `1`, `3`, `5`

Sample method output
    `35`

![image1](images/01.png)

**Coding exercise**
Create a class `Point` with three properties: `x`, `y`, and `z`.

    class Point:

        def __init__(self):
            self.x = x
            self.y = y
            self.z = z

        def sqSum(self):
            pass

## Challenge 2: Implement a Calculator Class

🔴 In this exercise, you have to implement a calculator that can perform addition, subtraction, multiplication, and division.

**Problem statement**
Write a Python class called Calculator by completing the tasks below:

*Task 1*

👉 **Initializer**

Implement an initializer to initialize the values of num1 and num2.
Properties

    • num1
    • num2

*Task 2*

👉 **Methods**

    •add() is a method that returns the sum of num1 and num2.
    •subtract() is a method that returns the subtraction of num1 from num2.
    •multiply() is a method that returns the product of num1 and num2.
    •divide() is a method that returns the division of num2 by num1.

Input
    - Pass numbers (integers or floats) in the initializer.

Output
    - addition, subtraction, division, and multiplication

Sample input

    obj = Calculator(10, 94)
    obj.add()
    obj.subtract()
    obj.multiply()
    obj.divide()

Sample output

    104
    84
    940
    9.4

Coding exercise

    class Calculator:

        def __init__(self):
            pass
        def add(self):
            pass
        def subtract(self):
            pass
        def multiply(self):
            pass
        def divide(self):
            pass
