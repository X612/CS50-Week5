# CS50 Week 5

This repository contains my solutions for Week 5 of Harvard's **CS50x: Introduction to Computer Science**.

---

## 📚 Overview

In Week 5, I explored custom data structures, memory allocation, and performance optimization in C. I learned how to build dynamic structures to store and search data efficiently, managing memory manually using pointers.

### Topics Covered
- Abstract Data Types (Queues, Stacks)
- Linked Lists (Nodes, Dynamic Allocation)
- Trees & Binary Search Trees (BST)
- Hash Tables & Hash Functions
- Tries (Prefix Trees)
- Algorithm Efficiency & Big $O$ Notation

---

## 📂 Completed Problems

### 🩸 Inheritance
Simulates the inheritance of blood types across multiple generations using dynamically allocated family tree structures.
- **Language:** C
- **Key Concepts:** Recursion, Structs, Dynamic Memory Management

### 🔤 Speller
A high-performance spell-checker that loads a dictionary into memory using a **Hash Table** data structure to check a text file for misspelled words in minimum time.
- **Language:** C
- **Key Concepts:** Hash Tables, Hash Functions, Memory Leak Prevention (`valgrind`)

---

## 🛠️ Language & Environment

- **Language:** C
- **Compiler:** `clang` / `make`
- **Memory Debugger:** `valgrind`
- **Environment:** VS Code (CS50 Codespaces)

---

## ⚡ Quick Start

To compile and run the programs locally:

```bash
# Inheritance
make inheritance
./inheritance

# Speller
make speller
./speller texts/lalaland.txt
