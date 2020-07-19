# Fundamentals
Principles of Computer Science and Programming

---

## 1 SOLID Principles
### 1-1 Single Responsibility Principle:
A class should only have one reason to change; *Separation of concerns*.

A class should have only a single responsibility — that is, only changes to one part of the software's specification should be able to affect the specification of the class.

### 1-2 Open-Closed Principle:
Classes should be open for extension but closed for modification.

Software entities should be open for extension, but closed for modification.

### 1-3 Liskov Substitution Principle:
You should be able to substitute a base type for a subtype.

Objects in a program should be replaceable with instances of their subtypes without altering the correctness of that program.

### 1-4 Interface Segregation Principle:
Don't put too much into an interface; *YAGNI*; split into separate interfaces.

### 1-5 Dependency Inversion Principle:
High-level modules should not depend upon low-level ones; use abstraction.

Entities must depend on abstractions, not on concrete implementations.

---

## 2 Design Patterns
### 2-1 Creational Patterns:
The construction (creation) of objects.
#### 2-1-1 Builder
Used when object construction is complicated.
It's piecewise.
#### 2-1-2 Factory Method
#### 2-1-3 Abstract Factory
Used when object creation logic becomes too convoluted, the constructor is not descriptive.
It's non-piecewise.
Can be outsourced (A separate function, a separate class, hierarchy of factories).
A component responsible solely for the wholesale (not piecewise) creation of objects.

### 2-2 Structural Patterns:
The structure of classes (e.g. class members).

### 2-3 Behavioral Patterns:
No central theme (they are all different).

---

