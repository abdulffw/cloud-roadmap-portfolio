# Day 01 -- OS + Linux + VM + repo foundations

## 0) Today's Outcomes (Copy from the day doc)

-[ ] Complete Coursera Work
-[ ] Do 2 Hands-on Labs
-[ ] Ship 1+ work-quality artifacts
-[ ] Commit everything to Git
-[ ] Work in your repo the entire day (notes+labs+runbooks)
-[ ] Write down evidence (command output/screenshots) as you go
-[ ] If something breaks, capture the exact error message and add it to ERROR_LOG


## 1) Concept Primer Notes (in your own words)

Key Terms:
- CPU (Central Processing Unit): The "brain" of the computer that executes the instructions .
- RAM (Random Access Memory): Short term memory used to run programs, memory is lost when power is off.
- Storage (SSD/HDD): Long term place where files are saved, memory is saved long term even when power is off.
- OS (Operating System): The managing unit that controls all the hardware and runs the programs
- Linux: A type of OS that uses many operating systems which are built around the Linux Kernal.
- Terminal/Shells: A text based method to control the OS by typing commands which gives instructions to the OS.
- VM (Virtual Machine): A computer which is installed within a computer.
- Snapshot: A savepoint which you can always go back to in case of errors or mistrials.


## 2) Coursera Progress Log


Date:Jan 11, 2026

Course: Google IT Support: Technical Support Fundamentals

Module/Week Title: Module 1: Introduction To IT

Items Completed:
-Program Introduction
-What is IT?
-What does an IT Support Specialist do?
-Course Introduction
-Get started with your Google IT Support Certificate
-Helpful resources and tips
-Google IT Cert Participant Entry Survey
-Reflection: Your IT support path ahead
-From Abacus to Analytic Engine
-The Path to Modern Computers
-Pioneers in Computing and IT
-Kevin: Their career path
-Computer Language
-Character Encoding
-Binary
-Supplement Reading on Logic Gates
-Binary Conversion
-Binary
-Abstraction
-Computer Architecture Overview
-Kevin: Advice for the world of IT
-Computer Architecture
-Glossary terms from course 1, module 1
-How to Count in Binary
-Module 1 challenge: Introduction to IT and Computing

Quiz Score:
- Reflection: Your IT support path ahead (practice assignment): 100%
- Binary (practice assignment): 80%
- Computer Architecture (practice assignment): 100%
- How to Count in Binary (practice assignment): 100%
- Module 1 challenge: Introduction to IT and Computing (graded assignment): 97.5%

Key Takeaways:
- Converting decimal numbers into binary and vice-versa was easier than i thought when I understood the fundamentals of it.
- 4 concepts of IT fundamentals are hardware, OS, Software and Users
- Two types of character encoding are ASCII which is the older version, also known as base-2 numeral system and the other character encoding standard is UTF-8 which is used today.

Next Up: <Module 2: Hardware>


## 3) Step-by-step Lab log (what you did)
1. Cloned my Github repo to Ubuntu
2. Created a snapshot
3. Created a file, moved it, renamed it and deleted it on a terminal

## 4) Evidence (Commands + outputs + what it proves)
Copy/Paste outputs directly (do not rewrite errors)

Example:

```bash

git --version

```

Output:

```

<paste output here>

```

what this proves:

-



## 5) Troubleshooting (only if something broke)

### Symptom:
### Exact error message:
### Cause (your best guess):
### Fix steps:
### Verification:


## 6) Knowledge Check Answers (TAILORED -- answer the questions from today's day doc)
Q1: In one sentence each, what does the CPU do? What does the RAM do? What does storage do?
A1: CPU controls the hardware and instructs it what to do. RAM stores short term memory and powers the software and hardware to complete instructions. Storage stores memory and saves files and documents permenantly even when power is off.
Q2: What is an Operating System(OS) responsible for? Name 3 responsibilities.
A2: Operating System controls the hardware and runs programs. Decides which programs to run, when and how much CPU processing. Manages the RAM and how much ram is given to each program and prevents overwriting. Organizes files and folder and controls access to hardware.
Q3: What is a VM snapshot and when should you take one?
A3: A VM snapshot is a save point in which you can return to. You should take on before you start to expirement so if anything breaks you can restore the VM to when you created the snapshot
Q4: If a command fails, what information should you copy into your notes so you can debug later?
A4: You should copy the error you got and other symptoms and also how you fixed it
Q5: Why do cloud jobs care so much about linux?
A5: Cloud systems run on Linux


## 7) Reflection (general questions allowed here)
Q1: What part of today felt the most confusing, and what made it confusing?
A1: The note taking part was the most confusing because all the notes and logs i am doing is currently done on Ubuntu, and this is all new to me. I believe if I continue to do it and get the hang of it I will become adjusted to it and perform better.
Q2: If you had to teach a friend what a VM is, what example would you use?
A2: I would use my computer as an example, i would say that the VM is a computer within a computer, its just virtual and there is no permenant damage that can be done.
Q3: What is one thing you did today that you could repeat tomorrow without looking?
A3: I can continue to convert binary and decimal values


## 8) Tomorrow's Plan (1-3 bullets)



## LAB NOTES ##

# What does each of these commands do?

- cd    -> cd changes the directory you want to be in
- ls    -> ls lists all the folders within the directory
- pwd   -> pwd shows where you are currently and which directory your in
- mkdir -> mkdir creates a new directory
- touch -> touch creates a new empty file
- nano  -> nano redirects you to the file editor of the file you selected
- cat   -> shows the contents of the file
- cp    -> cp copies a folder or file
- mv    -> mv either moves the file or folder and also renames it
- rm    -> rm deletes file or folder
