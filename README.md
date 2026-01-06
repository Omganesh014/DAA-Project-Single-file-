# Restaurant Management System (C++)

## Overview
This project is a comprehensive **Restaurant Management System** developed in **C++** as part of an academic requirement, with a strong emphasis on **data structures, algorithms, and system design principles**.

Although implemented as a **single translation unit**, the system follows an **enterprise-style architecture** using **namespace-based logical modularity**, ensuring high cohesion, low coupling, and clean separation of concerns.

The project goes beyond basic CRUD functionality and demonstrates **real-world problem modeling**, **algorithmic efficiency**, and **defensive software engineering practices**.

---

## System Architecture Overview

This project models real-world restaurant operations within a single, cohesive application. The system manages:

Customer records and loyalty programs

Order lifecycle and kitchen workflows

Inventory management with low-stock alerts

Billing, payments, and refunds

Table reservations and waitlisting

Delivery routing and optimization

Promotions, feedback, and analytics

All components are integrated while maintaining clear logical boundaries between business logic, data structures, and algorithms.

---

## Architectural Design

### Single-File by Requirement
The system is intentionally implemented as a **single `.cpp` file** due to academic submission constraints.


## Data Structures Used

Data Structure	Purpose

AVL Tree	Fast customer lookup

Max Heap	Priority-based order processing

Hash Table	Inventory management

Dynamic Hash Table	Auto-resizing inventory

Linked List Queue	Kitchen order workflow

Circular Queue	Billing queue

Graph	Delivery routing

LRU Cache	Hot data caching

## Algorithms Implemented

Searching

Binary Search

Hash-based lookup

KMP / Rabin-Karp (string matching)

Sorting

Merge Sort

Quick Sort

Heap Sort

Graph Algorithms

BFS & DFS

Dijkstra’s Algorithm (standard & optimized)

Prim’s Minimum Spanning Tree (standard & optimized)

Greedy Algorithms

Nearest Neighbor heuristic (TSP approximation)

Resource allocation strategies

These algorithms are applied to realistic scenarios such as order prioritization, inventory lookup, delivery route optimization, and analytics.

## Academic Note

This project prioritizes clarity, correctness, and algorithmic rigor over external frameworks or libraries.
The design intentionally mirrors real-world systems while respecting academic constraints.

## Conclusion

This project represents a transition from basic procedural programming to system-level software design, showcasing the ability to design, implement, and reason about scalable, maintainable, and defensible software systems under real-world constraints.

```txt
WHY SINGLE FILE?
- Academic submission requirement
- Ensures portability and zero build issues
- Simplifies grading and evaluation
- No dependency on external headers
