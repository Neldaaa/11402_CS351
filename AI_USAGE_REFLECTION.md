# Comprehensive Learning & AI Usage Reflection

- **Student Name:** 阮清閒 
- **Student ID:** 1123564
- **Course:** CS351: AI-assisted Software Development

## 1. How My AI Workflow Changed

**Phase 1: Just Asking for Code (The Beginning)**
<div align="justify">
At the start of the course, I just asked AI tools simple questions like, "Write a C++ Two Sum function". The AI gave me code very fast, but it caused a lot of problems. The code didn't match my project's file structure, and it failed when I tested it with duplicate numbers. I spent more time fixing the AI's mistakes than actually learning. </div>

**Phase 2: Learning to Give Rules (Assignment 2 & Project 0)**
<div align="justify">
  
When I learned about SDD (Specification-Driven Development), BDD (Behavior-Driven Development), and TDD (Test-Driven Development), my way of working completely changed. I realized that AI is just a fast typist, I have to be the engineer. I started writing the rules *before* I opened the AI chat. 
*   **My New Prompt Style:** Instead of a general request, I gave the AI exact instructions. For Project 0, I told the AI: "Write a C++20 `twoSumHashTable` function. It must return `[-1, -1]` if there is no pair, and it must handle duplicate numbers properly." Because I gave strict rules, the AI gave me exactly what I needed on the first try. </div>

**Phase 3: Using AI to Debug and Learn (Project B)**
<div align="justify">
  
By the time I worked on Project B (the CSV Mini Database), I stopped using AI to write big files of code. I only used it to help me fix hard bugs. 
*   **Fixing Docker & CMake:** When my Docker container failed to build the project, I copied the CMake error log into the AI. I didn't ask the AI to just give me the fixed code. I asked it to *explain* why it was failing. This actually helped me learn how C++ compiling work. </div>

## 2. What I Really Learned in This Course
<div align="justify">
  
Writing code is only a small part of software engineering. My biggest takeaways are:

*   **Rules Must Come First:** I learned that if I don't make sure about basic rules before I start, the AI will make the project very messy. I have to set the standards first, and then force the AI to follow them.
*   **Tests Prove the Truth (TDD):** I used to look at AI code and just guess if it was correct. For Project B, I wrote test cases manually *before* finishing the main code. When the AI helped me write the query filtering logic, I ran my tests. If the tests failed, I knew the AI was wrong and I made it fix the logic. The tests protected my project.
*   **Connecting the Steps:** I learned how to be organized. Every change I made was connected. A project idea became a Jira story, which became a Git branch, which turned into a Pull Request, and finally got merged into `main`. This showed me how real software teams work together safely.
</div>
<div align="justify">

***Conclusion: This course taught me that AI cannot replace the human engineering process, it requires the engineering process to function properly. AI is a powerful assistant for writing boilerplate code or finding syntax errors, but it lacks the critical thinking needed to design system architecture or understand user needs. SDD, BDD, and TDD are the necessary guardrails that keep AI-assisted development safe, traceable, and professional. We must remain the architects, using AI strictly as our builder.***
</div>
