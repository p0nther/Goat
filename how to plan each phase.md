To plan each individual phase using Scott Young’s **Ultralearning** framework, you run a **3-Step Process** for every single phase before you start studying: **Metalearning $\rightarrow$ Structure Construction $\rightarrow$ System Execution**.

---

### Step 1: Phase Metalearning (Spend the First 10% of Time)

Before opening page 1 or starting a lab, allocate 2–4 days to map out the specific phase:

* **Identify the 20% Core Concept Engine:** Pinpoint the foundational mechanisms that drive the entire phase.
* *Phase 1:* Syscalls, process memory layout, TCP/IP handshake.
* *Phase 3:* Stack frames, instruction pointer manipulation, x86-64 assembly calling conventions.


* **Filter and Prune Textbooks:** Apply Scott’s **Emphasize/Exclude** rule. Do *not* read cover-to-cover. Strip out irrelevant or outdated chapters.
* **Select the "Exam" Benchmark:** Establish an uncheatable, objective test of competence before beginning.

---

### Step 2: Build the Phase Structure (Apply the 1:2 Rule)

Divide your total estimated hours into **Theory Blocks** and **Lab Blocks**.

$$\text{Phase Hours} = \text{Theory Hours (7–10 pages/hr)} + \text{Lab Hours (Theory Hours} \times 2)$$

Using **Phase 1** (~600 target pages) at your 7–10 pages/hour reading pace:

* **Theory Allocation:** $600 \text{ pages} \div 8.5 \text{ pgs/hr} \approx \mathbf{70 \text{ hours}}$
* **Lab Allocation (1:2 Rule):** $70 \times 2 = \mathbf{140 \text{ hours}}$
* **Total Phase Budget:** $210 \text{ hours} \div 35 \text{ hrs/week} \approx \mathbf{6 \text{ Weeks}}$

---

### Step 3: Set Up the Daily System Execution

Divide your 5-hour daily study block into two distinct engines using key Ultralearning tactics:

```
[ Daily 5-Hour Execution Engine ]
  ├── Block 1 (1.5 Hours): Direct Theory & Retrieval
  └── Block 2 (3.5 Hours): Hands-on Direct Execution & Drills

```

#### 1. Block 1 (1.5 Hours): Theory & Active Retrieval

* **Read for Direct Application:** Read 10–15 pages *only* to solve immediate lab problems.
* **Retrieval Practice:** Close the book. Draw the memory structure, network protocol header, or execution flow completely from memory. Do not highlight text.

#### 2. Block 2 (3.5 Hours): Direct Execution & Drills

* **Directness:** Work directly inside the target environment (GDB, Ghidra, PortSwigger, pwn.college).
* **Drill Strategy:** If you hit a bottleneck (e.g., struggling to parse assembly instructions in GDB), halt the lab. Run a 2-day dedicated "Drill Block" focusing strictly on disassembling small C binaries until reading assembly is automatic.
* **Overkill Method:** Extend the textbook exercises. Write custom automation scripts in Python/Go rather than using pre-built tools.

---

### Step 4: Execute the "Phase Exam" & Retrospective

At the end of the calculated timeline (e.g., Week 6 for Phase 1):

1. **Attempt the Benchmark:** Complete your predefined "Final Exam" (e.g., write the custom raw-socket sniffer and solve all required pwn.college modules without looking at hints).
2. **Evaluate Performance:**
* **Pass:** Move immediately to the Metalearning phase of Phase 2.
* **Fail:** Identify the exact weakness, add a 1-week "Drill Block," and re-attempt the benchmark.
