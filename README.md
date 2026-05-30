# 🧬 Python MRO Explorer

### Mastering Inheritance, Method Overriding & Method Resolution Order

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.x-3776AB?logo=python">
  <img src="https://img.shields.io/badge/OOP-Inheritance-success">
  <img src="https://img.shields.io/badge/Concept-MRO-orange">
  <img src="https://img.shields.io/badge/Level-Beginner_to_Intermediate-blueviolet">
</p>

---

## 🌟 Project Vision

Object-Oriented Programming is not just about creating classes; it is about designing relationships between them.

This repository explores how Python navigates those relationships using **Method Resolution Order (MRO)** and demonstrates how inherited methods can be customized through **method overriding**.

Through practical examples inspired by real-world systems, this project transforms theoretical OOP concepts into interactive Python implementations.

---

## 🚀 What You'll Discover

🔹 How Python searches for methods in inheritance hierarchies

🔹 How derived classes override parent class behavior

🔹 How MRO determines which method executes

🔹 How inheritance promotes code reusability

🔹 How polymorphism creates flexible program designs

---

# 📚 Learning Modules

## 🚗 Vehicle Management System

A simulation of different vehicle types inheriting common functionality from a shared parent class.

### Classes Included

```text
Vehicle
 ├── Car
 ├── Bicycle
 └── Motorcycle
```

### Concepts Demonstrated

✨ Inheritance

✨ Method Overriding

✨ Dynamic Method Dispatch

✨ MRO Tracing

---

## 🔺 Geometry & Shape Analyzer

A hierarchy of geometric shapes sharing common behaviors while implementing their own calculations.

### Classes Included

```text
Shapes
 ├── Circle
 ├── Rectangle
 └── Triangle
```

### Concepts Demonstrated

✨ Polymorphism

✨ Method Specialization

✨ Mathematical Computation

✨ MRO Tracing

---

# 🏗 Repository Architecture

```text
Python-MRO-Inheritance-Lab
│
├── 01_Vehicle_MRO_Tracing.py
├── 02_Shape_MRO_Tracing.py
│
└── README.md
```

---

# 🔍 Understanding MRO

Method Resolution Order (MRO) defines the sequence Python follows while searching for methods in an inheritance chain.

For example:

```python
Car.mro()
```

returns:

```text
[Car, Vehicle, object]
```

Python checks:

1. Car
2. Vehicle
3. object

and executes the first matching method it finds.

This mechanism becomes even more powerful in complex inheritance structures.

---

# 💡 Why This Project Matters

Understanding MRO is essential for:

🎯 Building scalable applications

🎯 Designing reusable class hierarchies

🎯 Working with frameworks that heavily rely on inheritance

🎯 Writing maintainable object-oriented code

🎯 Preparing for technical interviews and university practicals

---

# 🛠 Technologies Used

| Technology   | Purpose                    |
| ------------ | -------------------------- |
| Python 3     | Programming Language       |
| OOP          | Software Design            |
| Inheritance  | Code Reusability           |
| Polymorphism | Dynamic Behavior           |
| MRO          | Method Resolution Analysis |

---

# 🎓 Ideal For

✔ Computer Science Students

✔ Python Learners

✔ OOP Enthusiasts

✔ Laboratory Practicals

✔ Technical Interview Preparation

✔ GitHub Portfolio Enhancement

---

# 🌈 Key Takeaway

> "Inheritance defines relationships. Method Overriding defines behavior. MRO decides the path."

Understanding these three concepts is the foundation of writing elegant and scalable object-oriented Python programs.

---

## ⭐ Star this repository if it helped you understand MRO and Inheritance better!

### Happy Coding 🚀

### Keep Learning 📚

### Keep Building 💡

