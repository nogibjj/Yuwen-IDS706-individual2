## Duke IDS 706 Data Engineering individual project # 2
---

[![rs_ci](https://github.com/nogibjj/Yuwen-IDS706-individual2/actions/workflows/rs_cicd.yml/badge.svg)](https://github.com/nogibjj/Yuwen-IDS706-individual2/actions/workflows/rs_cicd.yml)

Youtube Link: 
https://youtu.be/MJBjX9fHs8E

---

**Summary**

The objective of this individual project is for a set of Rust functions for performing ETL operations on a dataset and CRUD operations a SQLite database.

Project Structure:

![Alt text](<str.jpeg>)

---
**Interaction with Copilot**

Asked copilot to help transform original python code into rust and write the Makefile for command line tools

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

Make result:
![Alt text](<cargo_result.png>)

make insert result:
![Alt text](<insert.png>)

make read result:
![Alt text](<read.png>)

make update result:
![Alt text](<update.png>)

make delete result:
![Alt text](<delete.png>)


