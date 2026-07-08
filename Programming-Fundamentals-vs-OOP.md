# Programming Fundamentals vs Object-Oriented Programming (OOP)

## Introduction

Programming Fundamentals and Object-Oriented Programming (OOP) are two important ideas in learning to code.
Programming Fundamentals covers the basic building blocks of writing software, while OOP introduces a way to organize code around objects and their behavior.
This document explains both concepts clearly and compares them side by side.

## Programming Fundamentals

Programming Fundamentals are the basic concepts used in almost every programming language.
Beginner-friendly core ideas include:

- **Variables**: store values like numbers or text.
- **Data types**: define the kind of values, such as integers, strings, and booleans.
- **Operators**: perform actions like addition, comparison, and assignment.
- **Control flow**: decide what code runs using `if`, `else`, `while`, and `for`.
- **Functions**: group code into reusable blocks that can be called with input values.
- **Input/output**: read data from users or files and display results.

## Core OOP Concepts

Object-Oriented Programming is a way to model software using objects that combine data and behavior.
The main concepts are:

- **Classes**: templates or blueprints for creating objects.
- **Objects**: actual instances of classes with their own data.
- **Encapsulation**: keeps an object's data and behavior together and hides internal details.
- **Inheritance**: lets a class use features from another class.
- **Polymorphism**: allows different objects to be used through the same interface.
- **Abstraction**: focuses on essential features while hiding complexity.

## Comparison Table

| Feature | Programming Fundamentals | Object-Oriented Programming (OOP) |
|---|---|---|
| Main focus | Basic code structure and logic | Organizing code into objects and relationships |
| Data handling | Separate from functions | Combined inside objects |
| Reusability | Functions and modules | Classes and inheritance |
| Complexity | Easier for simple tasks | Helps manage larger systems |
| Best for | Small scripts and learning basics | Applications with many related entities |
| Example style | Procedural / step-by-step | Model objects and interactions |

## Advantages and Disadvantages

### Programming Fundamentals

Advantages:
- Easier to learn first
- Good for simple scripts and small programs
- Works in any language

Disadvantages:
- Can become hard to manage in large projects
- Less natural for modeling real-world entities
- Code may repeat more often

### Object-Oriented Programming (OOP)

Advantages:
- Helps organize complex systems
- Encourages reusable code with classes
- Makes it easier to model real-world concepts

Disadvantages:
- Requires more planning and structure
- Can be more difficult for beginners at first
- May add overhead for very small programs

## Simple Code Examples

### Programming Fundamentals Example

```python
# A simple function to add two numbers

def add_numbers(a, b):
    return a + b

result = add_numbers(3, 5)
print("Sum:", result)
```

### OOP Example

```python
# A class for a simple bank account

class BankAccount:
    def __init__(self, owner, balance=0):
        self.owner = owner
        self.balance = balance

    def deposit(self, amount):
        self.balance += amount

    def withdraw(self, amount):
        if amount <= self.balance:
            self.balance -= amount
            return True
        return False

account = BankAccount("Ali", 100)
account.deposit(50)
print(account.balance)  # 150
```

## Conclusion

Programming Fundamentals are the first step in learning how to code. They teach the basic building blocks of logic, data, and control flow.
OOP builds on those fundamentals by organizing code around objects, making it easier to manage larger applications and model real-world ideas.
Both styles are useful: start with fundamentals, and use OOP when your program grows in size or complexity.
