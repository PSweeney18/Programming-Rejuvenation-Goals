# Programming-Rejuvenation-Goals
Laying out Goals for what I want to accomplish in the next 3 months

---

# Programming Roadmap (Nov 2025 → Feb 2026)

This document outlines the full multi-month plan for completing **Gitlet**, **BYOW**, **Personal Website**, **CS 224N**, **Neetcode 150**, and optional compiler work.
Deadlines are grouped by semester and ordered by priority.

---

# 📌 High-Level Deadlines

| Project                                    | Deadline     |
| ------------------------------------------ | ------------ |
| **Gitlet (Refactor + Merge + Extensions)** | **Dec 31**   |
| **BYOW Enhancements**                      | **Dec 31**   |
| **Personal Website**                       | **Dec 31**   |
| **CS 224N (Lectures + HW)**                | **Jan 16**   |
| **Neetcode 150 (Java)**                    | **Feb 1**    |
| **CS 224N Final Project (GPT-2)**          | After Jan 16 |
| **Optional: Write a C Compiler**           | No deadline  |


Low-Level Deadlines


Got it — let’s make a **more detailed and specific calendar**, week-by-week with realistic expectations. I’ll break it into **tasks per project per week**, estimating hours where reasonable. I’ll assume today is **Nov 18, 2025**, and the main deadlines are:

* Gitlet, BYOW, Personal Website → **Dec 31**
* CS 224N Lectures + HWs → **Jan 16** (but acknowledge that finishing everything may extend)
* Neetcode 150 → **Feb 1**
* GPT-2 final project (Gai Saber) → after Jan 16

I’ll aim for a **balanced workload**, factoring in realistic completion times.

---

# 📆 Programming Calendar (Nov 18 → Feb 1, 2026)

---

## **🟪 NOVEMBER 18–30**

**Goals:** Refactor Gitlet & BYOW, start merge, basic website setup, light Neetcode.

### **Nov 18–23**

* **Gitlet**

  * SOLID refactor: separate Repository, Commit, Blob logic (5–6 hours)
  * Plan merge algorithm (2–3 hours)
* **BYOW**

  * Clean up world generation code (2–3 hours)
* **Website**

  * Set up VPS, Apache, domain, SSL (3–4 hours)
* **Neetcode**

  * 2–3 easy problems (1–2 hours/day)

### **Nov 24–30**

* **Gitlet**

  * Implement Split Point algorithm (3–4 hours)
  * Start handling simple merge cases (modified in one branch) (3–4 hours)
* **BYOW**

  * Refactor room generation + map logic (3–4 hours)
* **Website**

  * Skeleton for homepage and project pages (3–4 hours)
* **Neetcode**

  * Continue 2–3/day (1–2 hours/day)

---

## **🟩 DECEMBER 2025**

**Goals:** Gitlet full merge + remote commands, BYOW upgrades, launch personal site, Neetcode steady progress.

### **Dec 1–7**

* **Gitlet**

  * Complete all merge file-case logic (6–8 hours)
  * Begin conflict handler (2–3 hours)
* **BYOW**

  * Implement optional terrain features or small improvements (3–4 hours)
* **Website**

  * Basic blog Flask setup (3–4 hours)
* **Neetcode**

  * Solve ~12–14 problems this week (2 hours/day)

### **Dec 8–14**

* **Gitlet**

  * Implement add-remote, rm-remote (3–4 hours)
  * Test merge with multiple branches (3–4 hours)
* **BYOW**

  * Test enhancements + bug fixes (2–3 hours)
* **Website**

  * Start deploying local Flask project on VPS (3–4 hours)
* **Neetcode**

  * 12–14 problems this week

### **Dec 15–21**

* **Gitlet**

  * Implement push, fetch, pull (5–6 hours)
  * Write tests for remote commands (3–4 hours)
* **BYOW**

  * Polish visuals / tile rendering / HUD (3–4 hours)
* **Website**

  * Resume page + project showcase complete (3–4 hours)
* **Neetcode**

  * 12–14 problems (2 hours/day)

### **Dec 22–31**

* **Gitlet**

  * Final integration testing, debugging (6–8 hours)
  * Documentation polish (2 hours)
* **BYOW**

  * Final touches, commit fully working version (3–4 hours)
* **Website**

  * Deploy blog live with basic posts (3–4 hours)
* **Neetcode**

  * Maintain 2/day or catch up if behind (1–2 hours/day)

> **Deadlines:** Gitlet, BYOW, Personal Website → Dec 31

---

## **🟦 JANUARY 2026 (Jan 1–16)**

**Goals:** CS 224N Lectures + HWs (partial realistic), Neetcode, GPT-2 planning.

> Note: Completing all lectures + HWs by Jan 16 may be tight; focus on core HWs first.

### **Jan 1–4**

* **CS 224N**

  * Lectures 1–5 (watch + take notes) (3–4 hours/day)
  * HW1: Word vectors and basic NLP (3–4 hours total)
* **Neetcode**

  * 3–4 problems/day (1–2 hours/day)

### **Jan 5–11**

* **CS 224N**

  * Lectures 6–12 (3–4 hours/day)
  * HW2: Dependency parsing (3–4 hours total)
* **Neetcode**

  * 3–4 problems/day

### **Jan 12–16**

* **CS 224N**

  * Lectures 13–23 (2–3 hours/day)
  * HW3–5: Try to complete essentials (may need to extend into late Jan)
* **Neetcode**

  * 3–4 problems/day
* **GPT-2 planning**

  * Begin reading GPT-2 papers + PyTorch starter templates (1–2 hours/day)

---

## **🟥 JAN 17 – FEB 1**

**Goals:** Neetcode completion, GPT-2 final project setup & initial prototype.

### **Jan 17–23**

* **Neetcode**

  * Focus on final problems (4–5/day, 2 hours/day)
* **GPT-2**

  * Implement model skeleton
  * Tokenizer / dataset pipeline
  * Test on small text samples

### **Jan 24–31**

* **Neetcode**

  * Finish remaining problems (2–3/day)
* **GPT-2**

  * Start training small-scale GPT-2
  * Experiment with poetry translation pipeline

### **Feb 1**

* **Neetcode 150 complete** 🎉
* GPT-2 prototype ongoing

---

# **Tips for Staying on Track**

* Track **daily tasks in a simple planner** (even 1–2 lines/day).
* Always finish **1 small module per project per week**.
* If behind on CS 224N, prioritize **HW completion over lectures**.
* Reserve weekends for **longer work sessions** (~4–6 hours) on Gitlet / BYOW / Website during Nov–Dec.


---

# 1. 🔧 Code Refactoring / SOLID Work

## Apply SOLID Principles to:

* **Gitlet**
* **BYOW**

**Goals:**

* Reduce class responsibilities (SRP)
* Introduce dependency inversion to isolate I/O
* Decouple file system operations from logic
* Improve testability
* Clarify abstractions (Commit, Blob, Branch, Repository)

---

# 2. 🧬 Gitlet Full Merge Implementation

Implement and debug the `merge` command.
The full specification:

### **Definition:**

`java gitlet.Main merge [branch name]`

### Responsibilities:

1. **Find the Split Point**

   * Latest common ancestor between current branch and target.

2. **Handle Early-Exit Cases**

   * If given branch is ancestor of current → print:
     `Given branch is an ancestor of the current branch.`
   * If current branch is ancestor of given →
     print: `Current branch fast-forwarded.`
     and check out.

3. **File State Rules**
   Implement exhaustive behavior:

* Modified in given but not current → checkout + stage
* Modified in current but not given → keep
* Modified in same way → no change
* Absent at split; present only in current → keep
* Absent at split; present only in given → checkout + stage
* Present at split; removed in given → delete
* Present at split; removed in current → keep removed
* **Modified in different ways → conflict**

  * Write:

    ```
    <<<<<<< HEAD
    contents of file in current branch
    =======
    contents of file in given branch
    >>>>>>>
    ```

4. **Commit After Merge**

   * Commit message:
     `Merged [given branch] into [current branch].`
   * Parent order: current branch first, given branch second.

5. **Conflict Output**

   * If conflicts occur:
     `Encountered a merge conflict.`

### Failure Cases:

* Staged additions/removals →
  `You have uncommitted changes.`
* Branch does not exist →
  `A branch with that name does not exist.`
* Merging branch with itself →
  `Cannot merge a branch with itself.`
* Untracked file would be overwritten →
  `There is an untracked file in the way; delete it, or add and commit it first.`

---

# 3. 🌐 Gitlet Code Extensions

### **add-remote**

```
java gitlet.Main add-remote [remote name] [path]/.gitlet
```

Failure:

* Remote already exists

### **rm-remote**

Failure:

* Remote does not exist

### **push**

* Fast-forward only
* If branch absent remotely → create
  Failure:
* Remote not found
* Remote branch not ancestor of local head

### **fetch**

* Copy commits/blobs from remote to local
  Failure:
* Remote not found
* Remote missing branch

### **pull**

* Do fetch + merge
  Failure:
* Combo of fetch + merge failures

---

# 4. 🗺️ BYOW Improvements (Optional but Recommended)

* **Hexagonal world generation**
* **Cellular automata** (e.g., lakes, grasslands, erosion patterns)

---

# 5. 🌐 Personal Website (Due Dec 31)
Here’s a **clean, paste-ready update** to your README section about building your personal website.
I took your existing “Personal Website” section and **added in all the extra content you provided** (Nixihost, Apache, Certbot, FreeDNS, Namecheap, Flask tutorial) AND the note about hosting your resume + blog.

You can **copy/paste this directly** at the bottom of your README.

---

## 🌐 Personal Website — Infrastructure & Tools

I plan to build a personal website that will host **my resume** and a **blog** where I write about topics that interest me.
Below is the stack and services I’m using:

### **Hosting / DNS / SSL**

**Nixihost (VPS Provider)**
A private virtual server shared on a physical machine but isolated for my use.
It acts like a cheaper alternative to a dedicated server.
Cost: **$5/month**

**Apache (Web Server / Reverse Proxy)**
Used to route incoming requests to the website and forward them to the correct services.
Acts as the middleman between users and content.
Setup reference:
[https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-16-04](https://www.digitalocean.com/community/tutorials/how-to-set-up-apache-virtual-hosts-on-ubuntu-16-04)

**FreeDNS**
Used for managing domain name redirection and DNS namespaces.

**Certbot (Let’s Encrypt SSL)**
Generates free, automated TLS certificates.
Allows secure HTTPS connections.

**Namecheap**
Where domain names were purchased.
Cost: **~$7/year**

---

### **Web Framework / Blog**

I plan on building part of the site using **Flask**, especially for the blog component.

Tutorial reference:
**How to build a Flask app:**
[https://charlesleifer.com/blog/how-to-make-a-flask-blog-in-one-hour-or-less/](https://charlesleifer.com/blog/how-to-make-a-flask-blog-in-one-hour-or-less/)

---

### **Static Site Components**

The website will include:

* Interactive home page
* **Resume** (HTML/PDF embedded)
* **Blog** (Flask-driven or static-rendered)
* Links to Gitlet, BYOW, and other programming projects
* Future sections for NLP research (224N), poetry translation (Gai Saber), and more

---

# 6. 🤖 CS 224N (NLP) — Stanford

Complete by **Jan 16**:

### **Lectures (23 total)**

Watch Spring 2024 versions.

### **Assignments (5 total)**

Typical topics:

* Word vectors
* Dependency parsing
* Neural machine translation
* Transformers
* Question answering

### **Final Project**

Implement a **GPT-2 architecture**.
(After Jan 16).
Can integrate your **GAI Saber** poetry-preserving translation project.

---

# 7. 🧩 Leetcode (Neetcode 150)

**Finish in Java by Feb 1**

Daily target: **2–3 problems/day**
Weekly target: **14–20 problems**

Focus regions:

* Arrays & Hashing
* DP
* Graphs
* Sliding Window
* Trees
* Intervals

---

# 8. 🛠️ Optional Project — Write a C Compiler

Follow a compiler book such as:

* *Crafting a Compiler*
* *Modern Compiler Implementation in C*
* *Writing a C Compiler (Nora Sandler)*

Goals:

* Lexing
* Parsing
* Type checking
* IR
* Codegen (x86 or RISC-V)

No set deadline.

---

# 🗂️ Month-By-Month Timeline

### **November**

* Refactor Gitlet + BYOW with SOLID
* Begin Gitlet merge implementation
* Start Neetcode (lightly)

### **December**

* Finish Gitlet merge + remote commands
* Complete BYOW enhancements
* Launch Personal Website
* Continue Leetcode

**All three due Dec 31**

### **Early January**

* CS 224N Lectures (23)
* CS 224N HW 1–5
* Continue Neetcode

### **Mid-January**

* Finish CS 224N HW5
* Prepare GPT-2 final project (architecture)

### **Late January → February 1**

* Complete Neetcode 150
* Begin GPT-2 “Gai Saber” prototype
* (Optional) Start C compiler

---

Got it — here is a **clean, paste-ready block** containing ONLY the additional URLs you wanted, written in a nice section you can drop at the bottom of your README.

No duplication, no restating previous content — just a well-formatted section.

---

## 📚 Resources & Reference Links

### **CS 224N (NLP — Stanford)**

* **Lecture Videos (YouTube Playlist):**
  [https://www.youtube.com/watch?v=DzpHeXVSC5I&list=PLoROMvodv4rOaMFbaqxPDoLWjDaRAdP9D&index=1](https://www.youtube.com/watch?v=DzpHeXVSC5I&list=PLoROMvodv4rOaMFbaqxPDoLWjDaRAdP9D&index=1)

* **General Stanford Course Page:**
  [https://web.stanford.edu/class/cs224n/](https://web.stanford.edu/class/cs224n/)

---

### **Berkeley Projects**

* **Gitlet (Project 2):**
  [https://sp21.datastructur.es/materials/proj/proj2/proj2](https://sp21.datastructur.es/materials/proj/proj2/proj2)

* **BYOW – Build Your Own World (Project 3):**
  [https://sp21.datastructur.es/materials/proj/proj3/proj3](https://sp21.datastructur.es/materials/proj/proj3/proj3)

---

### **Algorithms / Interview Prep**

* **Neetcode 150 Practice Page:**
  [https://neetcode.io/practice?tab=neetcode150](https://neetcode.io/practice?tab=neetcode150)

---


