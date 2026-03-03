# 🧠 Operating System Scheduling & Memory Management Algorithms (Java)

![Java](https://img.shields.io/badge/Language-Java-blue)
![Domain](https://img.shields.io/badge/Domain-Operating%20Systems-critical)
![Focus](https://img.shields.io/badge/Focus-Algorithmic%20Analysis-orange)
![Level](https://img.shields.io/badge/Level-Core%20CS%20Strong-success)

---

## 📌 Overview

This repository contains Java implementations of fundamental Operating System algorithms focusing on:

- CPU Scheduling
- Memory Management (Page Replacement)
- Performance Metrics Analysis
- Comparative Algorithm Study

The goal of this project is not just implementation — but understanding:

- Algorithmic trade-offs  
- Throughput vs Response Time  
- Starvation & Fairness  
- Page Fault behavior  
- Scheduling efficiency  

This project reflects strong fundamentals in Core Computer Science concepts required for technical placements.

---

# 🧠 CPU Scheduling Algorithms Implemented

## 1️⃣ FCFS (First Come First Serve)
- Type: Non-Preemptive  
- Time Complexity: O(n)  
- Limitation: Convoy Effect  

## 2️⃣ SJF (Non-Preemptive)
- Type: Non-Preemptive  
- Time Complexity: O(n log n)  
- Minimizes average waiting time  
- May cause starvation  

## 3️⃣ Preemptive SJF (Shortest Remaining Time First)
- Type: Preemptive  
- Improves response time  
- Requires dynamic tracking of processes  

## 4️⃣ Priority Scheduling
- Both Preemptive & Non-Preemptive versions  
- May cause starvation  
- Can be improved using Aging  

## 5️⃣ Round Robin (RR)
- Type: Preemptive  
- Time Quantum based scheduling  
- Fair and responsive  
- Context switching overhead trade-off  

---

# 📊 CPU Scheduling Metrics Calculated

Each implementation computes:

- Waiting Time (WT)  
- Turnaround Time (TAT)  
- Completion Time (CT)  
- Average Waiting Time  
- Average Turnaround Time  

---

# 🧠 Page Replacement Algorithms Implemented

## 1️⃣ FIFO (First In First Out)
- Time Complexity: O(n)  
- Suffers from Belady’s Anomaly  

## 2️⃣ LRU (Least Recently Used)
- Based on temporal locality  
- Efficient with hashing  

## 3️⃣ MRU (Most Recently Used)
- Opposite of LRU  
- Performs well in specific patterns  

## 4️⃣ Optimal Page Replacement
- Theoretical best algorithm  
- Used for benchmarking  
- Replaces page used farthest in future  

---

# 📈 Memory Performance Metrics

- Number of Page Faults  
- Frame State after each reference  
- Hit Ratio  
- Fault Ratio  

---

# ⚡ Time Complexity Summary

| Algorithm | Time Complexity | Preemptive |
|------------|----------------|------------|
| FCFS | O(n) | No |
| SJF | O(n log n) | No |
| SRTF | O(n²) (simulation) | Yes |
| Priority | O(n log n) | Both |
| Round Robin | O(n × time slices) | Yes |
| FIFO | O(n) | — |
| LRU | O(n) / O(1)* | — |
| Optimal | O(n²) | — |

---

# 🏗️ Design Approach

- Structured procedural logic  
- Clear separation of scheduling logic and metric computation  
- Use of arrays, queues, and sorting  
- Simulation-based modeling  

---

# 🎯 Placement Relevance

This project demonstrates:

- Strong grasp of Operating System fundamentals  
- Understanding of scheduling trade-offs  
- Practical implementation of theoretical algorithms  
- Performance comparison skills  
- Awareness of starvation, fairness, and efficiency  

These topics are frequently asked in:
- Product-based company interviews  
- Core CS technical rounds  
- GATE and competitive exams  

---

# 🚀 How to Run

Compile:
javac FileName.java

Run:
java FileName

Example:
javac RR.java
java RR

---

# 🔮 Possible Enhancements

- Add Gantt Chart visualization  
- Add Aging mechanism  
- Implement Multi-Level Queue Scheduling  
- Add Clock Page Replacement  
- Create GUI-based simulator  

---

# 👩‍💻 Author

Sayali Kale  
Computer Engineering Student  
Interested in Core CS, Systems & Algorithms  
LinkedIn: www.linkedin.com/in/sayali-kale-42001a2b1 

---

⭐ If you found this helpful, consider starring the repository!
