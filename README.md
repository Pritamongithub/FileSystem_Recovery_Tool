# 💾 File System Recovery and Optimization Tool

Welcome to the official repository for the **File System Recovery and Optimization Tool**.  
This project simulates a block-based file system to demonstrate how operating systems manage storage, ensure data integrity, and recover from failures.

---

## 🧑‍💻 Project Overview

This project is an **interactive simulation of a block-based file system**, designed to showcase:

- How an Operating System manages physical storage  
- The role of **Inodes** in metadata handling  
- Techniques for **fault tolerance and recovery**  
- Optimization methods like **disk defragmentation**

---

## ⚙️ Key Features

- **🧱 Virtual Disk Engine**  
  Simulates a 4MB storage space divided into 1024 blocks (4KB each)

- **📂 Inode Metadata Management**  
  Tracks file names, sizes, and block allocation using structured inode tables

- **🗺️ Free-Space Management**  
  Uses a bitmap (`free_map`) to efficiently manage available disk blocks

- **💥 Crash Simulator**  
  Simulates hardware failures and power outages with random block corruption

- **🛠️ FSCK Recovery Module**  
  Scans the disk, detects inconsistencies, and restores file system integrity

- **🚀 Disk Defragmentation**  
  Optimizes storage by compacting fragmented blocks for better performance

---

## 🛠️ Technology Stack

- **Language:** C++  
- **Version Control:** Git & GitHub  
- **Tools:** VS Code, MinGW / GCC Compiler  

---

## 👥 Team Members

- **Pritam** – System Architecture & Optimization  
- **Ankit** – Fault Tolerance & Crash Simulation  
- **Maninder** – Metadata Logic & Recovery Engine  

---

## 📅 Development Timeline

| Date   | Milestone |
|--------|----------|
| Apr 1  | Project Setup & AI-Guided Architecture Planning |
| Apr 3  | Inode & Metadata Structure Implementation |
| Apr 5  | Block-Based Storage Allocation Logic |
| Apr 7  | Bitmap-Based Free Space Management |
| Apr 9  | Disk Crash Simulation & Corruption Logic |
| Apr 11 | FSCK Recovery Module & Consistency Checking |
| Apr 14 | Final Optimization (Defragmentation) & Documentation |

---

## 📌 Learning Outcomes

- Understanding of **file system internals**
- Hands-on implementation of **memory and storage management**
- Simulation of **real-world system failures**
- Practical exposure to **data recovery techniques**

---

## 🎓 Academic Context

> 📘 This project was developed as part of the **CSE-316 Operating Systems Coursework**.

---


> ⚠️ *This project is intended for educational purposes and demonstrates core Operating System concepts through simulation.*

