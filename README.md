## Duke IDS 706 Data Engineering individual project # 2
---

[![rs_ci](https://github.com/nogibjj/Yuwen-IDS706-individual2/actions/workflows/rs_cicd.yml/badge.svg)](https://github.com/nogibjj/Yuwen-IDS706-individual2/actions/workflows/rs_cicd.yml)

---

**Summary**

The objective of this individual project is for a set of Rust functions for performing ETL operations on a dataset and CRUD operations a SQLite database.

Project Structure:

![Alt text](<str.jpeg>)

---

**Code Location**

You can find the Rust functions and other codes in the following files:
- `src\main.py`
- `src\lib.py`

These functions enable the downloading a dataset, transform it into a sqlite database, and read queries.
---

**Preparations**

1. Create a codespace
2. build: cargo build
3. extract: cargo run extract
4. transform to database: cargo run transform
5. sample querys (Makefile): make create, make read, make update, make delete.

---

**Rust Result**

Make py_test result:
![Alt text](<cargo_result.png>)
