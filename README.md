✅ README.md — Module 03 (optimizado y alineado)
# 🐍 Python Garden — Data Quest  
### Mastering Python Collections for Data Engineering

Repository: **python03_data_quest**

**This repository is part of a personal Python learning journey focused on
clarity, mental models and explainable code.**

This module focuses on mastering Python’s core **collection types** and
applying them intentionally in data processing and analytics scenarios.
Exercises are framed around game analytics and data engineering–style
problems, but the concepts transfer directly to real-world pipelines.

This module builds on:

- **python00_basics** — execution flow and functions  
- **python01_structures** — object-oriented thinking  
- **python02_data_guard** — defensive programming and error handling  

---

## 🎯 Learning Objectives

By completing this module, the learner can:

- Work confidently with command-line input using `sys.argv`
- Choose the appropriate data structure for a given problem
- Process and analyze data using:
  - lists
  - tuples
  - sets
  - dictionaries
- Apply basic analytics (sum, average, min, max, ranges)
- Use comprehensions for clear and expressive transformations
- Handle invalid input gracefully without crashing
- Write code that is readable and easy to explain

The module prioritizes **clarity, correctness, and explainability**
over overengineered solutions.

---

## 🧠 Core Concepts Covered

- Command-line arguments (`sys.argv`)
- Python collections and their intended use cases:
  - **lists** for sequential and ordered data
  - **tuples** for structured and immutable data
  - **sets** for uniqueness and set-based analytics
  - **dictionaries** for labeled and relational data
- Basic statistics and aggregation
- Error handling with `try / except`
- Tuple unpacking
- Iteration patterns
- Generators and streaming data processing
- List / dict / set comprehensions
- Program execution flow and entry point

---

## 🧪 Exercises Overview & Learning Progression

Each exercise introduces a new data structure or processing pattern,
building progressively toward more expressive and efficient data handling.

### ex0 — Command Quest
**Concepts:** `sys.argv`, execution flow, loops  
- Reads arguments passed from the terminal  
- Distinguishes between program name and user arguments  
- Handles the case where no arguments are provided  
- Displays structured output following subject specifications  

📌 Focus: understanding how programs receive and interpret external input.

---

### ex1 — Score Analytics
**Concepts:** lists, basic stats, `try / except`  
- Receives numeric scores from the command line  
- Stores valid data in a list  
- Computes total, average, min, max, and range  
- Handles invalid input gracefully  

📌 Focus: why lists are ideal for sequential data processing.

---

### ex2 — Game Coordinate System
**Concepts:** tuples, unpacking, math, error handling  
- Represents 3D positions using tuples  
- Calculates Euclidean distance between points  
- Parses coordinates from strings  
- Uses tuple unpacking for clarity  

📌 Focus: working with structured, immutable data.

---

### ex3 — Achievement Tracker
**Concepts:** sets, set operations, analytics  
- Tracks unique achievements per player  
- Computes:
  - all unique achievements
  - shared achievements
  - rare achievements  
- Uses union, intersection, and difference  

📌 Focus: analytics without complex loops using set operations.

---

### ex4 — Inventory Master
**Concepts:** dictionaries, nested structures, controlled updates  
- Models inventories with nested dictionaries  
- Tracks quantities, categories, rarity, and values  
- Computes total inventory value and item counts  
- Performs controlled transactions  
- Produces analytical summaries  

📌 Focus: modeling complex relationships with dictionaries.

---

### ex5 — Data Stream
**Concepts:** iteration, generators, streaming data  
- Processes data incrementally using generators  
- Avoids storing large datasets in memory  
- Demonstrates streaming-oriented thinking  
- Handles edge cases safely  

📌 Focus: memory-efficient data processing.

---

### ex6 — Analytics Dashboard
**Concepts:** comprehensions, aggregation, formatting  
- Demonstrates:
  - list comprehensions
  - dict comprehensions
  - set comprehensions  
- Aggregates and analyzes data  
- Produces structured analytical output  

📌 Focus: expressive, readable data transformations.

---

## 🗂️ Project Structure



.
├── ex0/ ft_command_quest.py
├── ex1/ ft_score_analytics.py
├── ex2/ ft_coordinate_system.py
├── ex3/ ft_achievement_tracker.py
├── ex4/ ft_inventory_system.py
├── ex5/ ft_data_stream.py
├── ex6/ ft_analytics_dashboard.py
├── data_quest_tools/
├── en.subject.pdf
├── README.md
└── MAP.md


---

## ▶️ How to Run

From the root of the project:

```bash
python3 ex0/ft_command_quest.py hello world
python3 ex1/ft_score_analytics.py 1500 2300 1800
python3 ex2/ft_coordinate_system.py "(1,2,3)" "(4,5,6)"
python3 ex3/ft_achievement_tracker.py
python3 ex4/ft_inventory_system.py
python3 ex5/ft_data_stream.py
python3 ex6/ft_analytics_dashboard.py

📌 Notes

Only the Python standard library is used

Output format follows the subject specifications

No external dependencies

MAP.md documents the learning progression and design decisions

Helper scripts (if present) are for exploration and learning, not required
to understand or run the core exercises

🚀 Conclusion

Data Quest builds a foundation for data-oriented thinking in Python:
not only how to use collections, but when and why to choose each one.

By the end of the module, the learner can reason clearly about data
structures, processing patterns, and analytics design.

This module prepares the ground for:

file and stream processing

larger data pipelines

backend and data engineering workflows

📌 Module completed — Python Garden · Data Quest 🐍
