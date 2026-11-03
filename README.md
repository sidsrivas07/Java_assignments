# UCS553: Enterprise Web Application — Java Lab Assignments

Repository containing solutions to all 6 Java lab assignments for the **Enterprise Web Applications (UCS553)** course.

## Student Details
- **Name:** Siddhant Srivastava
- **Roll Number:** 1024030892
- **Batch:** 3C63

---

## Repository Structure

```
Java_assignments/
├── assignment1
├── assignment2/
│   ├── ques1 (week3)
│   └── ques2 (week3)
├── assignment_3
├── assignment4
├── assignment5
├── assignment6/
│   ├── ques1
│   ├── ques2
│   └── ques3
└── README.md
```

---

## Assignments Overview

### Assignment 1: Basic Programming Using Java
Focuses on fundamental Java programming, control flow, loops, and standard input/output.
- **Q1: Leap Year Checker** — Validates whether a given year is a leap year.
- **Q2: Alphabet Checker** — Determines whether an input character is an alphabetic letter.
- **Q3: Factorial Calculation** — Calculates factorial of a number using iterative loops.
- **Q4: Fibonacci Series** — Generates first *n* terms of the Fibonacci sequence.
- **Q5: Greatest Common Divisor (GCD)** — Computes GCD using the Euclidean algorithm.
- **Q6: Least Common Multiple (LCM)** — Calculates LCM using relationship between GCD and products.
- **Q7: Count Digits** — Counts total number of digits in an integer.
- **Q8: Reverse a Number** — Reverses the digits of an integer.
- **Q9: Power Calculation** — Computes power ($base^{exponent}$) iteratively.
- **Q10: Palindrome Checker** — Verifies if a number reads the same backwards as forwards.

---

### Assignment 2: Object-Oriented Programming (OOP)
Demonstrates abstraction, inheritance, polymorphism, encapsulation, and interfaces.
- **Question 1 (`ques1 (week3)`) — Online Food Delivery System:**
  - Abstract class `FoodOrder` with common order properties, static counters, and abstract delivery charge calculations.
  - Concrete classes `RegularOrder` and `PremiumOrder` implementing `Discountable` interface.
  - `OrderUtility` providing validation and summary reporting.
- **Question 2 (`ques2 (week3)`) — Smart University Library System:**
  - Abstract class `LibraryResource` tracking resources, title, author, and fine calculations.
  - `Book` and `DigitalResource` subclasses implementing `Printable` interface with distinct fine calculation models.
  - Input validation utility methods.

---

### Assignment 3: Exception Handling
Comprehensive exploration of built-in exceptions, nested blocks, custom exception hierarchies, and recovery mechanisms.
- **Q1: Exception Hierarchy Demonstration** — `ArithmeticException`, `NullPointerException`, `ArrayIndexOutOfBoundsException`, and `NumberFormatException`.
- **Q2: Nested Try-Catch Blocks** — Multi-level nested error handling.
- **Q3: Safe Calculator** — Handles division by zero, invalid numbers, and unknown operators.
- **Q4: Student Result Evaluation** — Custom `InvalidMarksException` with validation rules.
- **Q5: Banking Application** — Custom `InsufficientBalanceException`, `InvalidAmountException`, and `AccountNotFoundException`.
- **Q6: Secure Authentication System** — Multi-attempt authentication tracking with `InvalidUsernameException`, `InvalidPasswordException`, and `AccountLockedException`.
- **Q7: E-Commerce Shopping Cart** — Layered exception hierarchy (`ProductException`, `PaymentException`, `OrderException`).

---

### Assignment 4: Java Collections Framework
In-depth implementation of Java Collections (`List`, `Set`, `Map`, `Queue`, `Deque`).
- **Question 1 — University Course Registration Portal:**
  - Fast lookups and uniqueness enforcement via `HashMap` and `HashSet`.
  - Prerequisite validation and course capacity limits.
  - Waitlist management using `LinkedList` as a FIFO queue.
- **Question 2 — Music Streaming Media Player Queue:**
  - Doubly-linked playlist navigation (next, previous, repeat, shuffle).
  - Recently played history tracking with a bounded `ArrayDeque`.
  - Song lookup and metadata retrieval.

---

### Assignment 5: Generics, Enums & Optionals
Explores generic classes, bounded type parameters, wildcard types, `Optional`, and enums.
- **Q1: Generic Sum** — Bounded type parameter `<T extends Number>` to calculate numeric sums across types.
- **Q2: Student Email Lookup** — Null-safe programming using `java.util.Optional`.
- **Q3: Generic Student Result Evaluation** — Generic `Result<T extends Number>` model.
- **Q4: Event Manager** — Enum-driven event status and priority handling with generic registries.
- **Q5: Generic Utility Class** — Type-safe search, filter, and comparison operations with `Comparable<T>`.

---

### Assignment 6: File Handling & Object Serialization
Covers Java I/O streams, byte vs character streams, buffered streams, and serialization.
- **Question 1 (`ques1`) — Student File Manager:**
  - Binary file copying with `FileInputStream` / `FileOutputStream`.
  - Character and text processing with `FileReader`, `FileWriter`, and `BufferedReader`.
  - Throughput and latency benchmark between `Scanner` and `BufferedReader`.
- **Question 2 (`ques2`) — Server Log Analyzer:**
  - Line-by-line parsing of application logs.
  - Counts errors, warnings, and info entries; extracts targeted error details into summary reports.
- **Question 3 (`ques3`) — Employee Serialization:**
  - Object serialization and deserialization via `ObjectOutputStream` / `ObjectInputStream`.
  - Demonstrates security handling with `transient` fields (e.g. sensitive salary data).

---

## How to Run

Compile and run any assignment file using the standard Java development kit (JDK 8 or higher):

```bash
# Example for Assignment 1:
javac assignment1.java   # or compile specific class
java LeapYear

# Example for Assignment 2:
javac assignment2/ques1.java
java Main

# Example for Assignment 6:
javac assignment6/ques1.java
java StudentFileManager
```
