# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Anas Saeed Ali Alhijraf] |
| **Student ID** | [445050054] |
| **University Email** | [445050054]@std.psau.edu.sa |
| **GitHub Username** | [Anas05q] |
| **Repository Link** | [https://github.com/Anas05q/OS-Assignment1-Anas-Alhijraf] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log


 ### Entry 1 - [October 3, 2026]

**What I did:** Set up the assignment repository on GitHub.

**Details:**
- Forked the starter repository to my GitHub account.
- Prepared the project for working in VS Code.
- Started reviewing the assignment requirements.

**Challenges:** I needed to understand how to set up the repository and start working with the provided code.

**Solution:** I followed the setup steps and checked the project files.

**Time spent:** Approximately 1 hour.


 ### Entry 2 - [October 4, 2026]

**What I did:** Implemented Feature 1: Process Priority.

**Details:**
- Added a priority field to the Process class.
- Generated a random priority between 1 and 10 for each process.
- Updated the ready queue output to display the priority.
- Committed the changes to GitHub.

**Challenges:** I needed to understand how to add a new field to the Process class without changing the scheduling order.

**Solution:** I added the priority to the constructor and displayed it when the process entered the ready queue, while keeping the scheduling order unchanged.

**Time spent:** Approximately 2 hours.



### Entry 3 - [October 6, 2026]

**What I did:** Implemented Feature 2: Context Switch Counter.

**Details:**
- Added a static variable named `contextSwitches`.
- Incremented the counter before each `currentThread.start()`.
- Displayed the total number of context switches at the end of the simulation.
- Tested the feature and committed it to GitHub.

**Challenges:** I needed to find the correct place to increment the counter.

**Solution:** I reviewed the scheduling loop and placed `contextSwitches++` before `currentThread.start()`.

**Time spent:** Approximately 2 hours.

### Entry 4 - [October 8, 2026]

**What I did:** Implemented Feature 3: Waiting Time Tracking.

**Details:**
- Added variables to track the waiting time of each process.
- Used `System.currentTimeMillis()` to calculate waiting time.
- Created a summary table showing Burst Time, Waiting Time, and Turnaround Time.
- Ran the program and checked the results.
- Committed the feature to GitHub.

**Challenges:** I needed to understand how to calculate waiting time correctly when a process returns to the ready queue.

**Solution:** I recorded when each process entered the ready queue and calculated its waiting time before execution.

**Time spent:** Approximately 4 hours. 

### Entry 5 - [Date and Time]
**What I did**: Worked on the assignment documentation in MY_WORK.md.

**Details**: Completed the reflection questions and technical answers about threads, Round-Robin scheduling, the ready queue, and real-world applications.

**Challenges**: Understanding some thread states and explaining how the simulation works.

**Solution**: Reviewed the Java code and simulation output to understand the concepts better.

**Time spent**: 2 hours

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

> 💡 **TIP:** Fill this in **last**, after all entries are written.

**Total time spent on assignment**: [10-12]

**Most challenging part**: The most challenging part was implementing waiting time tracking because I needed to understand when each process enters the ready queue and starts execution.

**Most interesting learning**: I learned how Round-Robin scheduling works and how Java threads can simulate CPU execution and context switches.

**What I would do differently next time**: I would review the code more carefully before making changes and test each feature separately to find errors more easily.

---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** *(5-7 sentences)*

[I learned that multithreading allows a program to use multiple threads to perform tasks. In this assignment, I used Java threads to simulate processes in a Round-Robin scheduler. I learned that `Thread.start()` starts a thread and `Thread.join()` makes the main thread wait for it to finish. I also learned that `Thread.sleep()` can simulate CPU execution time. Each process gets a time quantum, and unfinished processes return to the ready queue. This assignment helped me understand how threads and CPU scheduling work together]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part of this assignment was implementing the waiting time feature. At first, I found it difficult to understand how to calculate the waiting time for each process. I needed to track when a process entered the ready queue and when it started running. It was also important to avoid counting CPU execution time as waiting time. I reviewed the code and added the required variables step by step. After testing the program, I was able to display the waiting time and turnaround time for all processes]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I overcame the challenges by working on the assignment step by step. First, I reviewed the code to understand how the scheduler works. When I had difficulty understanding a feature, I asked for help and reviewed the explanation. I made small changes instead of modifying the entire program at once. After implementing the features, I ran the program and checked the output. This approach helped me complete the assignment and understand the code better.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading can be used in many real-world applications. For example, a web browser can use different threads to load pages and handle user actions. Video games can use threads for tasks such as sound and background loading. This helps applications remain responsive while performing multiple tasks. In my assignment, I learned how threads can be used to simulate CPU scheduling. I can apply this knowledge when developing programs that need to manage several tasks efficiently]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** *(3-5 sentences)*

[A process is an independent program with its own memory, while a thread is a smaller unit of execution that shares memory with other threads in the same process. Threads are usually faster to create and require fewer resources than separate processes. In my assignment, the `Process` class represents a simulated process, not a real operating system process. The `addProcessToQueue()` method uses `new Thread(process)` to create a Java thread for each execution. We used threads because they are easier to manage and allow us to simulate Round-Robin scheduling within one Java program.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[In Round-Robin scheduling, if a process does not finish within its time quantum, it returns to the ready queue. In my simulation, process P3 had a burst time of 7090 ms. P3 was re-queued one time before it finished. Re-queueing allows other processes to use the CPU instead of waiting for one process to finish completely. This makes CPU scheduling fairer for all processes]

Example from my output:
```
[P3 added to ready queue | Burst time: 7090ms | Priority: 7]
```

**Explanation of example:**
[This line shows P3 being added to the ready queue. It appeared twice in my output: once when P3 was first created and once when it was re-queued after using its time quantum]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1's thread is created using new Thread(process) inside addProcessToQueue()]

2. **Runnable**: [When currentThread.start() is called, P1's thread enters the RUNNABLE state]

3. **Running**: [The CPU executes P1's run() method. In Java, running is included in the RUNNABLE state]

4. **Waiting**: [When P1 calls Thread.sleep(), it enters TIMED_WAITING temporarily. Meanwhile, the main thread waits for P1 using Thread.join()]

5. **Terminated**: [When P1's run() method finishes, that thread enters the TERMINATED state]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [Name of scenario]

**Description**:
[An operating system manages multiple running programs that need CPU time. Round-Robin scheduling can give each runnable task a fixed time quantum. If a task does not finish, it returns to the ready queue.]

**Why Round-Robin works well here**:
[This approach improves fairness because tasks take turns using the CPU. A context switch allows the CPU to move from one task to another, similar to my simulation.]

### Example 2: [Name of application/scenario]

**Description**:
[A web server uses threads to handle requests from different users. Round-Robin scheduling can give each runnable thread a time quantum to perform CPU work. If a thread needs more CPU time, it can continue during another turn.]

**Why Round-Robin works well here**:
[This helps prevent one CPU-intensive request from using the CPU for too long. It improves responsiveness and gives other runnable threads a fair chance to execute.]

## Summary

**Key concepts I understood through these questions:**
1. The difference between processes and threads.
2. How Round-Robin scheduling uses the ready queue and time quantum.
3. How context switching and thread lifecycle work.

**Concepts I need to study more:**
1. How Java manages different thread states.
2. How operating systems perform context switching in real situations.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.

