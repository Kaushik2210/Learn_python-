# 🐍 Learn Python — From Zero to Advanced (Notes + Challenges + Exam Prep + Projects)

![Python](https://img.shields.io/badge/python-3.10%2B-blue?logo=python&logoColor=white)
![Notebooks](https://img.shields.io/badge/notebooks-49-orange?logo=jupyter&logoColor=white)
![Challenges](https://img.shields.io/badge/challenge%20problems-108-brightgreen)
![License](https://img.shields.io/badge/license-MIT-lightgrey)

A complete, hands-on Python course built as **Jupyter notebooks**. Every concept has a detailed explanation, runnable examples, exam corner questions, "hidden facts & pro tricks", and practice problems with automatic checking.

> **Start with:** [`notes/00_START_HERE.ipynb`](notes/00_START_HERE.ipynb) → then follow the modules in order. Use the [`STUDY_PLAN.md`](STUDY_PLAN.md) for a week-by-week schedule.

---

## 📁 Folder map

```
Learn_Python/
├── README.md                ← you are here
├── STUDY_PLAN.md            ← 8-week course plan + 2-week exam sprint + daily routine
├── requirements.txt         ← optional libraries (numpy, pandas, matplotlib)
│
├── notes/                   ← 21 lesson notebooks (00 – 20)
├── challenges/              ← 9 practice notebooks (108 problems) with ✅/❌ auto-tests
├── solutions/               ← worked solutions (peek after a real attempt!)
├── exam_prep/               ← cheat-sheet · 145 viva Q&A · 35 output puzzles · 2 mock papers · 16 debug drills
└── projects/                ← 5 capstone projects (OOP, AI game, SQL, security, data analysis)
```

## 📚 Notes (read + run + tinker)

| # | Notebook | You will learn |
|---|---|---|
| 00 | `00_START_HERE` | Course map, setup check, how to study |
| 01 | `01_Introduction_and_Setup` | What Python is, how it runs, errors, PEP 8, keywords |
| 02 | `02_Variables_Types_Operators` | Types, casting, every operator, precedence, mutability |
| 03 | `03_Strings` | Indexing/slicing, all methods, formatting, classic string programs |
| 04 | `04_Input_Output_Conditionals` | `input()`, if/elif/else, ternary, `match-case` |
| 05 | `05_Loops` | while/for, range, break/continue/else, patterns, number programs |
| 06 | `06_Lists` | Methods, sorting, copying (shallow/deep), comprehensions, matrices |
| 07 | `07_Tuples_Sets_Dicts` | Hashing, set algebra, dict patterns, Counter/defaultdict |
| 08 | `08_Functions` | Arguments, `*args/**kwargs`, scope (LEGB), lambda, closures, recursion |
| 09 | `09_Iterators_Generators_Decorators` | Iterator protocol, `yield`, decorators, context managers |
| 10 | `10_Modules_and_Standard_Library` | Imports, packages, venv/pip, a tour of the stdlib |
| 11 | `11_Exceptions` | try/except/else/finally, custom exceptions, exception groups |
| 12 | `12_File_Handling` | Text/binary, CSV, JSON, pickle, pathlib, SQLite |
| 13 | `13_OOP_Part1_Classes_Objects` | Classes, dunder methods, properties, dataclasses, `__slots__` |
| 14 | `14_OOP_Part2_Inheritance_Polymorphism` | Inheritance, MRO, ABCs, composition, design patterns |
| 15 | `15_Recursion_Algorithms_Complexity` | Recursion, DP, Big-O, searching, sorting, patterns |
| 16 | `16_Data_Structures` | Stack, queue, linked list, BST, heap, hash table, graphs |
| 17 | `17_Regular_Expressions` | Regex syntax, groups, lookarounds, real-world recipes |
| 18 | `18_NumPy_Pandas_Matplotlib` | Arrays, DataFrames, groupby, merge, pivots, plots |
| 19 | `19_Advanced_Python` | Typing, memory, threads/processes/asyncio, testing, profiling |
| 20 | `20_Python_Secrets_and_Tricks` | Easter eggs, gotchas, one-liners, performance & tooling secrets |

Every notebook ends with **📝 Exam Corner** (likely theory questions + output prediction) and a **✅ Summary**. Most also contain a **🕵️ Hidden Facts & Pro Tricks** section.

## 🏋️ Challenges (practice)

| Notebook | Topics | Problems |
|---|---|---|
| `01_Basics_Strings` | operators, strings, ciphers, Roman numerals | 12 |
| `02_Control_Flow` | conditionals, loops, patterns, number theory | 12 |
| `03_Collections` | lists, sets, dicts, matrices, intervals | 12 |
| `04_Functions` | args, closures, decorators, generators | 12 |
| `05_Files_Exceptions` | try/except, files, CSV, JSON | 12 |
| `06_OOP` | classes, inheritance, ABCs, dataclasses | 12 |
| `07_Algorithms_DataStructures` | recursion, DP, sorting, linked list, BST, graphs, LRU | 12 |
| `08_NumPy_Pandas` | arrays, broadcasting, DataFrames, merging | 12 |
| `09_Boss_Level` | regex, parser, interview puzzles, tic-tac-toe engine | 12 |

**How they work:** write your code in the *starter* cell → run the *test* cell → see ✅ PASS / ❌ FAIL. Problems are tagged 🟢 easy · 🟡 medium · 🔴 hard · 💀 brutal, with collapsible 💡 hints. The `solutions/` notebooks are fully worked and every test in them passes.

## 🎯 Exam prep

| Notebook | Use it for |
|---|---|
| `E01_Cheat_Sheet` | Last-night revision of everything on ~10 screens + the "30 programs examiners love" |
| `E02_Viva_and_Theory_Questions` | 145 Q&As for viva/theory answers (say them aloud) |
| `E03_Output_Prediction_Bank` | 35 "what is the output?" puzzles with on-demand answers |
| `E04_Mock_Exam_Papers` | Two 100-mark papers (short answers / explain / programs) with model answers |
| `E05_Find_The_Bug` | 16 debugging drills with hints, tests and explanations |

## 🚀 Projects

1. **Expense Tracker** – OOP, JSON persistence, custom exceptions, tests
2. **Unbeatable Tic-Tac-Toe** – recursion, minimax, memoisation, alpha-beta
3. **Student Management (SQLite)** – schema design, SQL joins/aggregates, transactions
4. **Password Toolkit** – `secrets`, entropy, salted PBKDF2 hashing, lockout logic
5. **Sales Data Analysis** – cleaning, feature engineering, groupby, RFM segmentation

---

## ▶️ How to run

**Option A — VS Code (easiest):** install Python + the *Python* and *Jupyter* extensions → open any `.ipynb` → *Select Kernel* → `Shift+Enter` to run a cell.

**Option B — Jupyter in the browser:**
```bash
pip install notebook
jupyter notebook
```

**Optional libraries** (needed for Module 18, Project 3's pandas step, Project 5, and the Matplotlib charts):
```bash
pip install -r requirements.txt
```

Everything else uses only Python's standard library. Python **3.10+** is required (uses `match-case`); the notes were verified on Python 3.13.

## ✅ Quality notes
- Every code cell in the notes, exam prep and projects was executed to embed its output. All of them except Module 04 (which needs typed answers — checked with simulated input) were also re-run top to bottom in a real Jupyter kernel.
- All 108 challenge problems have a worked solution whose tests all pass. The challenge notebooks themselves ship with unsolved starters, so they show ❌ until you solve them.
- Cells that cannot run unattended (typed input, interactive loops) say so in a comment. The Matplotlib chart cells were **not rendered** while building (Matplotlib wasn't installed) — they print an install hint if the library is missing and draw the charts once you `pip install matplotlib`.
- Results that depend on time, randomness or your computer (timings, random passwords) will differ slightly on your machine — that's expected.

## 🧭 Suggested path
1. Modules 01–07 (foundations) → do challenges 01–03
2. Modules 08–12 (functions, modules, errors, files) → challenges 04–05
3. Modules 13–14 (OOP) → challenge 06 → Projects 1 & 3
4. Modules 15–17 (algorithms, data structures, regex) → challenges 07 & 09 → Project 2
5. Modules 18–20 (data science, advanced, tricks) → challenge 08 → Projects 4 & 5
6. **Two weeks before exams:** `exam_prep/` daily (see `STUDY_PLAN.md`)

Happy coding! 🐍
