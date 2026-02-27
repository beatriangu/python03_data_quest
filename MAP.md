🧭 MAP.md — Python Garden · Data Quest
python03_data_quest — Collections & Data Processing

This document is my learning and design map.
It explains how my reasoning evolves throughout the module and how each exercise adds a new layer to conscious data handling in Python.

This is not a list of exercises.
It is a mental ladder.

It accompanies the code as a guide for understanding, defense, and review.

🌱 Core Idea

Move from:

❌ “I have scattered data”
to
✅ “I know how to represent, process, and analyze it”

Key principle:
👉 Choosing the right data structure matters more than the algorithm.

🟢 ex0 — Command Quest
🎯 Focus

→ Receiving data from outside the program.

🧠 I Learn

sys.argv

Script name vs user arguments

Execution flow

🧩 Mental Model

The program does not live in isolation.
The external world sends data.

🔗 Prepares For

Real input handling

Input validation

🟢 ex1 — Score Analytics
🎯 Focus

→ Processing sequential data.

🧠 I Learn

Lists

Accumulation

Basic statistics

try / except

🧩 Mental Model

Data often arrives in sequence.
Lists are the natural container.

🔗 Depends On

Correct input handling (ex0)

🔗 Prepares For

More structured analysis

🟢 ex2 — Game Coordinate System
🎯 Focus

→ Structured and fixed data.

🧠 I Learn

Tuples

Immutability

Tuple unpacking

Mathematical calculations

Format validation

🧩 Mental Model

Some data should not change.
Structure communicates intent.

(x, y, z)  →  position
not  →  generic list
🔗 Depends On

Basic processing (ex1)

🔗 Prepares For

Semantically meaningful data

🟢 ex3 — Achievement Tracker
🎯 Focus

→ Uniqueness and logical comparison.

🧠 I Learn

Sets

Automatic duplicate removal

Operations:

union

intersection

difference

🧩 Mental Model

Not everything is counting.
Sometimes it is comparing collections.

🔗 Prepares For

Cleaner analytics without complex loops

🟢 ex4 — Inventory Master
🎯 Focus

→ Complex data relationships.

🧠 I Learn

Dictionaries

Nested structures

Key → value modeling

Domain modeling

Player
└── inventory
    ├── item
    │   ├── quantity
    │   ├── rarity
    │   └── value
🧩 Mental Model

When there are relationships → use a dictionary.
Data has names.

🔗 Depends On

Understanding simple collections

🔗 Prepares For

Real-world systems

🟢 ex5 — Data Stream
🎯 Focus

→ Processing data without loading everything at once.

🧠 I Learn

Iterators

Generators

Incremental processing

Streaming mindset

🧩 Mental Model

Not everything fits in memory.
Process data as it arrives.

🔗 Prepares For

Files

Streams

Pipelines

🟢 ex6 — Analytics Dashboard
🎯 Focus

→ Expressive and concise data transformation.

🧠 I Learn

List comprehensions

Dict comprehensions

Set comprehensions

Aggregation

Output formatting

🧩 Final Insight

Code can be:

short

readable

expressive

without sacrificing clarity.

🔗 Integrates

The entire module

🧠 Global Evolution
ex0 → input
ex1 → sequence
ex2 → structure
ex3 → uniqueness
ex4 → relationships
ex5 → streaming
ex6 → expression

These are not isolated exercises.
They build judgment for working with data.

🎯 Final Objective

Be able to explain:

Why I chose this data structure

What problem it solves

What would happen with another option

How the approach scales

This MAP is my compass for the module and reflects how I think about data processing in Python.
