# CS112 Object-Oriented Programming — Lab Task #08 (Java)

This repository introduces **Java programming fundamentals** and **Graphical User Interface (GUI)** development using **AWT** and **Swing** libraries. Designed for beginners, it bridges core OOP concepts (classes, constructors, methods) with real-world interactive applications.

## 🎯 Learning Objectives

- ✅ Create Java classes with **constructors** and **methods**
- ✅ Handle user input using `Scanner`
- ✅ Implement **method overloading** via simple arithmetic operations
- ✅ Build **event-driven GUIs** using:
  - **AWT** (Abstract Window Toolkit)
  - **Swing** (`JFrame`, `JButton`, `JTextField`, `JOptionPane`)
- ✅ Understand **event handling** with `ActionListener`

---

## 📂 Lab Tasks Overview

### 🔢 Task 1 & 2: Basic Arithmetic Operations (Console)
- **Task 1**: Integer addition/subtraction via user menu
- **Task 2**: Float multiplication/division with loop support (`do-while`)
- Demonstrates **user interaction**, **conditional logic**, and **input validation**

### 👤 Task 3: Student Class (OOP Basics)
- `Student` class with:
  - `name` (String), `age` (int)
  - Parameterized constructor
  - `display()` method
- Shows **encapsulation** and **object instantiation**

### 🖥️ Task 4: AWT GUI — Button Grid
- Uses **AWT** (`Frame`, `Panel`, `Button`, `Label`)
- 10 buttons in a 2×5 grid
- Click any button → label updates: *"You pressed Button: X"*
- Implements **anonymous inner class** for `ActionListener`

### 💬 Task 5: Swing GUI — Name Greeting App
- Uses **Swing** (`JFrame`, `JLabel`, `JTextField`, `JButton`)
- Enter name → click "Submit" → shows **Arabic greeting** via `JOptionPane`
- Clean, modern look with layout management (`FlowLayout`)

---

## 💡 Key Concepts Illustrated

| Concept | Example |
|--------|--------|
| **Class & Object** | `Student std = new Student("Ali", 20);` |
| **Constructor** | `Student(String name, int age)` |
| **Event Handling** | `button.addActionListener(e -> {...})` |
| **AWT vs Swing** | AWT = native OS widgets; Swing = lightweight, customizable |
| **User Input** | `Scanner sc = new Scanner(System.in);` |

---

GUI Programs (Tasks 4–5)
# Task 4 (AWT)
javac AwtButtonExample.java
java AwtButtonExample

# Task 5 (Swing)
javac Main.java
java Main


Task 4 (AWT)

┌──────────────────────────────┐
│        AWT GUI EXAMPLE       │
├──────────────────────────────┤
│ [Button: 0] [Button: 1] ...  │
│ [Button: 5] [Button: 6] ...  │
├──────────────────────────────┤
│ You pressed Button: 3        │
└──────────────────────────────┘



Task 5 (Swing)
Input field + Submit button → pops up: "السلام عليكم Shahram!"


## ▶️ How to Run (in IntelliJ IDEA)

1. **Clone this repo**
   ```bash
   git clone https://github.com/ShahramXTech/OOP-Basic-Part-8.git
   
👤 About Me
   Shahram Tariq | @ShahramXTech
BS Software Engineering — Air University Kamra
