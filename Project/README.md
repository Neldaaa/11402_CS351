# 🚀 Course Projects - CS351: AI-assisted Software Development
<div align="justify">
This directory serves as the central hub linking to my separate project repositories for the CS351 course. To meet the Final Demo requirements, each project is hosted in its own independent repository to demonstrate repository hygiene, proper project structure, and isolated development environments. </div>

## 1. Project 0: Two Sum
🔗 **Repository Link:** [Project 0](https://github.com/Neldaaa/11402_CS351_Project0)

**🎯 Purpose:** 
<div align="justify">
This repository demonstrates my first complete software development experience using GitHub and AI-assisted tools. 
It solves the classic Two Sum problem using C++ while enforcing a professional build and testing discipline.
</div>

**💡 Key Implementations & Features:**
<div align="justify">
  
*   **Algorithms:** Implemented both a brute-force approach (`TwoSumArray`) and a single-pass hash map approach (`TwoSumHashtable`).
*   **Comprehensive Testing:** Developed unit tests covering standard cases, negative numbers, large numbers, duplicate values, no-solution edge cases, and a 10,000-element stress test, etc.
*   **CI/CD Pipeline:** Configured a GitHub Actions workflow that automatically builds the C++20 code and runs unit tests on push and pull request events.
*   **Containerization:** Included a `Dockerfile` to ensure the project builds and runs consistently across different environments.
</div>


## 2. Project B: CSV Mini Database & Query Engine
🔗 **Repository Link:** [Project B](https://github.com/Neldaaa/11402_CS351_ProjectB)

**🎯 Purpose:** 
<div align="justify">
This repository demonstrates a more complex software development process by building a lightweight, in-memory CSV data management system and query engine from scratch using C++.
</div>

**💡 Key Implementations & Features:**
<div align="justify">
  
*   **CSV Parsing & Data Handling:** Built a parser capable of reading CSV data, inferring types, and handling edge cases like missing fields and quoted text.
*   **Query Execution:** Engineered a system to execute SQL-like queries, supporting `SELECT` projections, `WHERE` filters, `ORDER BY`, `LIMIT` operations.
*   **Test-Driven Architecture:** Designed a comprehensive test suite verifying parser accuracy, complex query logic, indexing, and robustness against malformed inputs.
*   **Project Structure:** Separated the architecture logically into Storage (parser/database), Query Engine, and Interface layers, supported by CMake and Docker build environments.
</div>
