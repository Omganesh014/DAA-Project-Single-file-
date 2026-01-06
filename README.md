# Restaurant Management System (C++)

## Overview
This project is a comprehensive **Restaurant Management System** developed in **C++** as part of an academic requirement, with a strong emphasis on **data structures, algorithms, and system design principles**.

Although implemented as a **single translation unit**, the system follows an **enterprise-style architecture** using **namespace-based logical modularity**, ensuring high cohesion, low coupling, and clean separation of concerns.

The project goes beyond basic CRUD functionality and demonstrates **real-world problem modeling**, **algorithmic efficiency**, and **defensive software engineering practices**.

---

## Architectural Design

### Single-File by Requirement
The system is intentionally implemented as a **single `.cpp` file** due to academic submission constraints.

```txt
WHY SINGLE FILE?
- Academic submission requirement
- Ensures portability and zero build issues
- Simplifies grading and evaluation
- No dependency on external headers

This project is a comprehensive Restaurant Management System implemented entirely in C++, designed to model real-world restaurant operations using core data structures, algorithms, and system design principles.

The system manages customers, orders, kitchen workflows, inventory, billing, reservations, delivery routing, promotions, feedback, and analytics within a single, cohesive application. While developed as a single-file program due to academic constraints, the project enforces enterprise-style modularity through logical separation using namespaces and service-oriented design.

A key architectural highlight is the use of a Finite State Machine (FSM) for order lifecycle management, ensuring only valid state transitions occur (e.g., preventing refunds on unserved orders). This eliminates fragile string-based logic and enforces business rules at the type level.

The project demonstrates practical usage of AVL Trees, Heaps, Hash Tables, Queues, Graphs, and Caching mechanisms, along with optimized implementations of Dijkstra’s Algorithm, Prim’s Minimum Spanning Tree, BFS, DFS, sorting, searching, and greedy heuristics. These algorithms are applied to realistic problems such as priority-based order handling, inventory lookup, delivery route optimization, and analytics.

Special emphasis is placed on defensive programming, including input validation, structured logging, memory cleanup, error handling, file-based persistence (CSV/TXT), and auditability. All design trade-offs and simplifications are explicitly documented to maintain clarity and academic integrity.

Overall, this project represents a transition from basic procedural programming to system-level thinking, showcasing the ability to design, implement, and reason about scalable, maintainable software under real-world constraints.
