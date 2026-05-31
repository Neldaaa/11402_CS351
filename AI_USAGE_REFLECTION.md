# Comprehensive Learning & AI Usage Reflection

## 1. The Evolution of My AI Workflow (Quá trình thay đổi cách dùng AI)

**Phase 1: The "Blind Trust" Stage (Early Course)**
Initially, I treated AI as a shortcut to generate code quickly[cite: 2]. My prompts were unstructured (e.g., *"Write a C++ Two Sum function"*). The result was code that technically compiled but lacked proper error handling, ignored project file structures, and failed on edge cases like duplicate numbers[cite: 3]. I spent more time debugging AI hallucinations than actually engineering the software.

**Phase 2: The "Guardrail" Stage (Assignment II & Project 0)**
Learning about SDD, BDD, and TDD completely shifted my mindset[cite: 2]. I realized AI needs strict boundaries. I stopped asking AI to write logic first. Instead, I wrote the Specifications (SDD) and Test Cases (TDD) manually[cite: 2]. 
*   *My New Prompting Style:* I started feeding the AI exact constraints. For Project 0, I prompted: *"Write a C++20 `twoSumHashTable` function[cite: 3]. It must return `[-1, -1]` if no pair exists and handle duplicate values like `nums = [3, 3, 4], target = 6`[cite: 3]. Do not use external libraries."* This resulted in highly accurate code on the first try.

**Phase 3: The "Engineering Partner" Stage (Project B)**
By Project B (CSV Mini Database), I stopped using AI to write entire modules. Instead, I used it for highly targeted tasks[cite: 4]:
*   **Debugging CI/CD:** When my Docker container failed to build on Ubuntu 22.04[cite: 4], I provided the AI with the CMake error logs. Rather than asking for code, I asked it to *explain the cause* of the linking error, which helped me deeply understand C++ compilation.
*   **Brainstorming Edge Cases:** I used AI to brainstorm complex Gherkin (Given-When-Then) scenarios for malformed CSV inputs (TC-015)[cite: 4]. This ensured my Test Plan was bulletproof before I wrote the Query Engine logic.

## 2. What I Actually Learned (Reflection beyond the code)

Submitting working code is only a fraction of software engineering. Through this course, I learned:

*   **Standards Precede Generation:** Generating code is easy; maintaining it is the real challenge. I learned that defining strict Day 1 standards (e.g., file naming, `snake_case` for variables, `PascalCase` for classes) is mandatory before opening an AI prompt[cite: 2]. Without these rules, AI will destroy a repository's consistency.
*   **Traceability is King:** I learned how to link an Intended Use document to a Jira ticket, a Git branch, a Pull Request, and finally a unit test[cite: 2]. If AI generates a feature that cannot be traced back to an explicit requirement in `02_SRS.md`, it is out of scope and must be rejected[cite: 2].
*   **TDD as the Ultimate AI Validator:** I no longer read AI-generated code and assume it works. For Project B, I wrote the test suite (`TC-001` to `TC-016`) first[cite: 4]. If the AI's execution logic failed my tests, I knew the AI was wrong. This mindset shifted my role from a "code typist" to a "system reviewer."
