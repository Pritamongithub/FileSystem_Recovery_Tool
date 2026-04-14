\# File System Recovery and Optimization Tool



Project Overview:


This project is an interactive simulation of a block-based file system. It was designed to demonstrate how an Operating System manages physical storage, handles metadata via Inodes, and ensures data integrity through recovery mechanisms.



Key Features:


1. Virtual Disk Engine: Simulates a 4MB storage space divided into 1024 individual 4KB blocks.

2\. Inode Metadata Management: Uses a structured table to track file names, sizes, and the specific block indices where data is stored.

3\. Free-Space Management: Implements a Bitmap (free\_map) to efficiently track and allocate available blocks.

4\. Crash Simulator: A module designed to simulate hardware failures or power outages by introducing random block-level corruption.

5\. FSCK Recovery: A consistency check utility that scans the virtual disk, identifies damaged files, and attempts to restore system integrity.

6\. Disk Defragmentation: An optimization tool that compacts used blocks to improve sequential read/write throughput.



Technology Stack:


Language: C++

Version Control: Git \& GitHub

Tools: VS Code, MinGW / GCC Compiler



Group Members:


Pritam - System Architecture \& Optimization

Ankit - Fault Tolerance \& Crash Simulation

Maninder - Metadata Logic \& Recovery Engine


Development Timeline:


Apr 1: Project Setup \& AI-Guided Architecture Planning

Apr 3: Inode \& Metadata Structure Implementation

Apr 5: Block-Based Storage Allocation Logic

Apr 7: Bitmap-based Free Space Management

Apr 9: Disk Crash Simulation \& Corruption Logic

Apr 11: FSCK Recovery Module \& Consistency Checking

Apr 14: Final Optimization (Defrag) \& Documentation





\# Submitted for CSE-316 Operating Systems Coursework.



