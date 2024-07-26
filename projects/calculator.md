---
layout: project
type: project
image: img/calcimage.png
title: "Simple Arithmetic Calculator"
date: 2024
published: true
labels:
  - OOPs programming
  - C++
  - VS Code IDE
summary: "Designed an arithmetic calculator using OOP concepts in C++ to automate workplace computations."
---

<div class="text-center p-4">
  <img width="200px" src="../img/bandwcalc.png" class="img-thumbnail" >
</div>

**Arithematic Calculator in C++**

Project Description:
Developed a feature-rich calculator application using C++ with a focus on Object-Oriented Programming (OOP) concepts. The application supports basic arithmetic operations including addition, subtraction, multiplication, and division, providing a dynamic and interactive user experience.

**Key Features and Functions**
***User Input Handling***: Implemented robust methods to handle user inputs for values and operators, ensuring accurate and efficient data processing.
getvalue1() and getvalue2(): Functions to capture floating-point values from the user.
getOp(): Function to capture the operator and determine the required arithmetic operation or to terminate the program.
***Arithmetic Operations***: Developed dedicated methods for each arithmetic operation to perform calculations and display results.
add(): Adds two floating-point numbers and updates the result.
sub(): Subtracts the second number from the first and updates the result.
mul(): Multiplies two floating-point numbers and updates the result.
divide(): Divides the first number by the second and updates the result.

**Outcome and Impact**
Enhanced User Experience: The calculator provides real-time results and allows continuous operations without restarting the application.
Modular and Scalable Design: The use of OOP principles ensures that the code is modular, maintainable, and easy to extend with additional features.
Efficient Error Handling: Integrated error handling mechanisms to manage invalid inputs and prevent runtime errors, ensuring a smooth user experience.

Here is a code sample that illustrates the functions implemented in calculator application:

```cpp
#include <iostream>
using namespace std;

class Calculator {
public:
    float a, b, c;
    char op;

    void add();
    void sub();
    void mul();
    void divide();

    void getvalue1();
    void getvalue2();
    void getOp();
} obj;
```

You can learn more about the source code of calculator in my GitHub repository at [Simple Arithmetic Calculator](https://github.com/vmantrip762000/arithematic-calculator).
