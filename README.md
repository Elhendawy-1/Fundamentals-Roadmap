# Programming Fundamentals Roadmap

> Based on Dr. Mohammed Abu-Hadhoud's Complete Programming Curriculum — 24 Courses
> From [ProgrammingAdvices.com](https://programmingadvices.com)

An interactive single-page roadmap to track your progress through the full Programming Fundamentals path — from zero to professional C# / SQL developer.

**Live page:** `fundamentals-roadmap.html` (also published as `index.html` for GitHub Pages)

**Demo / Access password for the page:** `Fundamental@2026`

---

## What You Will Take

### Stage 1: Foundations & Core Programming (Courses 1-13)

Build your programming mindset and master C++ fundamentals, algorithms, OOP, and data structures.

| # | Course | What you learn |
|---|--------|----------------|
| 01 | **Programming Foundations - Level 1** `FREE` | Data → Wisdom, computer components, binary/hex/octal systems, networks intro, programming languages, variables, operators |
| 02 | **Algorithms & Problem-Solving Level 1** `FREE` | What is an algorithm, problem-solving mindset, flowcharts, pseudocode, conditions, loops, complexity intro |
| 03 | **Introduction to Programming with C++ - Level 1** `FREE` | Dev environment, first C++ program, variables, cin/cout, operators, if/switch, loops, functions, arrays, structs |
| 04 | **Algorithms & Problem-Solving - Level 1 (Solutions)** | 65 solved problems — step-by-step solutions for Level 1 |
| 05 | **Algorithms & Problem-Solving - Level 2** | 50 intermediate problems + 2 projects: Rock-Paper-Scissors, Math Quiz Game |
| 06 | **Introduction to Programming Using C++ Level 2** | Debugging, ternary, ranged loops, bitwise ops, functions overloading, recursion, vectors, pointers, references, `new`/`delete`, dynamic arrays |
| 07 | **Algorithms & Problem Solving Level 3** | Two Sum, Reverse String, Valid Parentheses, Merge Arrays, Max Subarray, Climbing Stairs, Stock, Binary Search + mini projects |
| 08 | **Algorithms & Problem Solving Level 4** | 65 advanced problems + Bank Extension project + ATM System project |
| 09 | **Foundations Level 2** | OSI, TCP/IP, IP/subnetting, DNS, HTTP, internet, client-server, security, VPN, cloud, virtualization, OS, Linux, CLI, Git, SDLC, Agile/Scrum |
| 10 | **OOP as it Should Be (Concepts)** | Classes/objects, access specifiers, constructors, inheritance, polymorphism, virtual/abstract, operator overloading, templates + Calculator, String Library, Date Library |
| 11 | **OOP as it Should Be (Applications)** | Utility lib, Input/Validation lib, full Bank System (clients, users, transactions, login, permissions, files), Currency Exchange |
| 12 | **Data Structures - Level 1** | Arrays, matrices, stack, vector, queue, singly/doubly/circular linked lists, ADT |
| 13 | **Algorithms & Problem Solving Level 5** | 8 full projects with Requirements → Solution → Extensions |

### Stage 2: Professional Development (Courses 14-24)

Master C#, databases, and real-world application development.

| # | Course | What you learn |
|---|--------|----------------|
| 14 | **C# - Level 1** | .NET, C# syntax, variables, operators, console I/O, conditions, loops, methods, arrays, strings, structs, enums, exceptions, Windows Forms, dialogs + Tic-Tac-Toe & Pizza projects, MDI |
| 15 | **Database Level 1 - SQL (Concepts and Practice)** | DB/RDBMS, keys, integrity, constraints, CREATE/INSERT/SELECT/WHERE/UPDATE/DELETE/ALTER, JOINs, aggregates, GROUP BY, subqueries, 1NF/2NF/3NF, backup/restore |
| 16 | **OOP As It Should Be In C#** | Classes, properties, constructors, static, inheritance, overriding, polymorphism, abstract, interfaces, sealed, indexer, events, delegates + Calculator |
| 17 | **Database - SQL (Projects & Practice)** | ER diagrams, complex SELECTs, multi-JOINs, stored procedures, views, indexes, triggers, transactions + Company/School/Hospital DB projects |
| 18 | **C# & Database Connectivity (ADO.NET)** | Connection/Command/DataReader, DataAdapter, DataTable/DataSet/DataView, parameterized queries, CRUD, pooling |
| 19 | **Full Real Project - DVLD** | Complete Driver Vehicle License Department system: DB design, DAL, BLL, People/Licenses/Applications/Tests/Users modules, login, permissions, reports |
| 20 | **C# Programming Level 2** | Generics, delegates, Func/Action, lambdas, events, LINQ, exceptions, files/streams, multi-threading, ThreadPool, async/await, TPL |
| 21 | **Database Level 2 - Concepts & T-SQL** | T-SQL vars, IF/CASE/WHILE, cursors, CTE/recursive CTE, procedures, scalar/table functions, window functions, OFFSET/FETCH, triggers, dynamic SQL, indexing, execution plans |
| 22 | **Data Structures Level 2 in C#** | List, ArrayList, Dictionary, HashSet, Hashtable, SortedList, LinkedList, BitArray, Stack/Queue, BST, AVL, Red-Black, Priority Queue, Min/Max Heap |
| 23 | **Algorithms Level 6** | Linear/Binary search, Bubble/Selection/Insertion/Merge/Quick sort, BFS/DFS, BST/AVL/RB algorithms, Graph BFS/DFS, Dijkstra, Greedy, DP, Knapsack |
| 24 | **Windows Services** | Service base class, lifecycle, OnStart/Stop/Pause, installer, ServiceController, debugging, timers, BackgroundWorker, real-world patterns |

---

## Features of This Page

- **Overall Progress Dashboard:** total courses (24), total lessons, completed, % progress
- **Filter Controls:** All / Free / Paid / C++ / C# / SQL / Algorithms / OOP / Data Structures
- **Course Cards:** number badge, FREE/PAID badge, description, tags, progress bar (`x/y lessons`), lesson preview
- **Course Modal:** click `View All Lessons` → full lesson list with durations, click to toggle completion
- **Progress Tracking with `localStorage`:** auto-save, restore on reload, Reset All Progress with confirm
- **Start / Continue Learning buttons:** deep links to `programmingadvices.com`
- **YouTube buttons:** free playlists for courses 1-3
- **Support & Coupons section:** SUPPORT25% / 50% / 75% / 100% with copy button
- **Responsive dark UI:** gradient `#0f0c29 → #302b63 → #24243e`, cyan `#00d2ff` / blue `#3a7bd5`, grid max-width 1400px, mobile breakpoint 768px
- **Password gate:** client-side gate (`Fundamental@2026`, stored in `sessionStorage`)

> Note: password + progress are client-side only (HTML/JS). Anyone can view source. Don't use for real security.

---

## How to Use

1. Open `fundamentals-roadmap.html` (or `index.html`) in any browser
2. Enter password: `Fundamental@2026`
3. View overall progress in the dashboard
4. Filter by Stage / Free / C++ / C# / SQL / Algorithms / OOP / DS
5. Click `Start Learning` / `Continue Learning` to go to the course
6. Click `View All Lessons` → click lessons to mark complete
7. Progress auto-saves to `localStorage`
8. Use `Reset All Progress` to start over

---

## Run Locally / GitHub Pages

```bash
# clone
git clone https://github.com/Elhendawy-1/Fundamentals-Roadmap.git
cd Fundamentals-Roadmap

# just open in browser (no build needed)
# Windows:
start fundamentals-roadmap.html
# macOS:
open index.html
# Linux:
xdg-open index.html
```

To enable GitHub Pages:
1. Push to GitHub
2. Repo → Settings → Pages → Deploy from branch → `main` / `/ (root)`
3. Open `https://Elhendawy-1.github.io/Fundamentals-Roadmap/`

Files:
- `fundamentals-roadmap.html` — main app
- `index.html` — identical copy for GitHub Pages root
- `prompt.md` — original spec for the page

No dependencies. Single HTML file with inline `<style>` + `<script>`. UTF-8, HTML5 semantic.

---

## Credits

- **Project by:** Elhendawy
- **Course content by:** Dr. Mohammed Abu-Hadhoud
- **Website:** https://programmingadvices.com
- **YouTube:** https://www.youtube.com/@ProgrammingAdvices
- **Roadmap page:** © 2026 Elhendawy. All Rights Reserved.

Course videos/materials belong to their respective owners. This repo only tracks progress and links to them.
