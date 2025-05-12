# 🗃️ Relational Database Management System (RDBMS)

A simple yet powerful **Relational Database Management System** implemented in **C++**, capable of storing, retrieving, and executing complex queries on large datasets. This project was built from scratch as a fun and educational exploration into how modern databases work under the hood.

---

## ✨ Features

- 🚀 **Custom LRU Buffer Manager**  
  Efficiently handles data larger than memory by paging disk blocks in and out of RAM using an LRU eviction policy.

- 🌳 **B+ Tree Indexing**  
  Enables fast lookup, insertion, and deletion operations while optimizing for disk I/O.

- 🧠 **Query Execution Engine**  
  Supports a suite of relational operators:
  - Table Scan
  - Hash Join
  - Sort-Merge Join
  - Selection
  - Aggregation

- 🧮 **Cost-Based Query Optimizer**  
  Automatically chooses the lowest-cost execution plan for a given query based on data statistics.
