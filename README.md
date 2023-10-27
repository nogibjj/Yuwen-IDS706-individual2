## Duke IDS 706 Data Engineering individual project # 2
---

[![rs_ci](https://github.com/nogibjj/Yuwen-IDS706-miniproject8/actions/workflows/rs_cicd.yml/badge.svg)](https://github.com/nogibjj/Yuwen-IDS706-miniproject8/actions/workflows/rs_cicd.yml)

---

**Summary**

The objective of this individual project is for a set of Rust functions for performing ETL operations on a dataset and CRUD operations a SQLite database.

---

**Code Location**

You can find the Rust functions and other codes in the following files:
- `src\main.py`
- `src\lib.py`



These functions enable the downloading a dataset and transform it into a sqlite database.
---


**Rust Result**

Make py_test result:
![Alt text](<py_test_result.png>)


---

**Result Comparison**

![Alt text](<py_result.png>)
![Alt text](<rs_result.png>)

Language | Running Time | CPU Usages | Memory Usage 
--- | --- | --- | --- 
Python | 0.0161s | 16.7% | 95.8% 
Rust | 2.32ms | 5.20% | 85.2% 

The numerical result shows that the Rust performance exceeds Python's running time, CPU usage, and memory usage in this specific case. Overall, Rust looks to be more efficient in this data analysis case.

Python's performance is hindered by its interpreted nature, dynamic typing, and resultant high CPU and elapsed time usage. In contrast, Rust's compiled design, strong typing, and memory control lead to efficient resource usage and shorter execution times, making it a better choice for high-performance and resource-efficient tasks.

