# ⚡ Parallel Graph Algorithms Benchmark (Single-Core vs Multi-Core)

🚀 A high-performance computing project that analyzes and benchmarks the execution efficiency of graph optimization algorithms in single-core and multi-core environments using OpenMP and C.

---

## 📌 Overview

This project studies the performance impact of parallelization on classic graph algorithms by comparing their execution on single-core (sequential) and multi-core (parallel) processors.

The objective is to evaluate:

* Execution time improvement
* CPU utilization
* Parallel efficiency
* Scalability of optimization algorithms

---

## 🧠 Algorithms Implemented

* 🔹 Dijkstra’s Algorithm (Shortest Path)
* 🔹 Kruskal’s Algorithm (Minimum Spanning Tree)
* 🔹 Prim’s Algorithm (Minimum Spanning Tree)

These algorithms were selected to analyze optimization behavior under different computational loads and parallelization patterns.

---

## 🏗️ System Design & Approach

### Single-Core Implementation

* Sequential execution
* One instruction at a time
* Lower CPU utilization
* Limited multitasking capability

### Multi-Core Implementation

* Parallel execution using OpenMP
* Thread-level parallelism
* Improved resource utilization
* Higher computational throughput

---

## ⚙️ Tech Stack

* 💻 Language: C
* 🧵 Parallel Programming: OpenMP
* 🖥️ OS: Linux/Unix
* 🧪 Benchmarking: Execution Time & CPU Usage Analysis
* 📊 Algorithms: Dijkstra, Kruskal, Prim

---

## 🔬 Methodology

1. Implemented graph algorithms in C (sequential version)
2. Parallelized core computation using OpenMP directives
3. Executed programs on single-core and multi-core configurations
4. Measured:

   * Execution Time
   * CPU Usage
   * Performance Speedup
5. Compared results across multiple runs for accuracy

---

## 📊 Performance Analysis

### 🔹 Dijkstra Algorithm

* Used for shortest path computation in weighted graphs
* Applications: Networking, routing systems, mapping engines

### 🔹 Kruskal Algorithm

* Constructs Minimum Spanning Tree (MST)
* Applications: Network design, clustering, circuit optimization

### 🔹 Prim Algorithm

* Greedy MST algorithm optimized for dense graphs
* Applications: Transportation planning, resource allocation

---

## 📈 Key Results

* Multi-core implementation showed significant reduction in execution time
* Improved CPU utilization due to parallel processing
* 20–35% performance improvement in computation-heavy workloads
* Better scalability for large graph inputs

---

## 🔥 Key Features

* Parallelized graph algorithms using OpenMP
* Performance benchmarking (Single vs Multi-core)
* CPU usage visualization
* Optimized multi-threaded execution
* Research-oriented implementation

---

## 🖥️ How to Run the Project

### Compile (Single-Core)

```bash
gcc dijkstra.c -o single_dijkstra
./single_dijkstra
```

### Compile (Multi-Core with OpenMP)

```bash
gcc -fopenmp multi_dijkstra.c -o multi_dijkstra
./multi_dijkstra
```

For Kruskal & Prim:

```bash
gcc -fopenmp multi_kruskal.c -o multi_kruskal
gcc -fopenmp multi_prim.c -o multi_prim
```

---

## 📁 Project Structure

```
parallel-graph-algorithms/
│
├── single_core/
│   ├── dijkstra.c
│   ├── kruskal.c
│   └── prim.c
│
├── multi_core/
│   ├── multi_dijkstra.c
│   ├── multi_kruskal.c
│   └── multi_prim.c
│
├── results/
│   ├── execution_time_analysis.png
│   └── cpu_usage_graphs.png
│
└── README.md
```

---

## 🎯 Learning Outcomes

* Parallel Computing & OpenMP
* Performance Optimization Techniques
* Multithreading & Synchronization
* Algorithm Efficiency Analysis
* High-Performance Computing Concepts

---

## 🌍 Real-World Applications

* High-performance computing systems
* AI & large-scale graph processing
* Network routing engines
* Distributed systems optimization
* Cloud computing workloads

---

## 🚀 Future Improvements

* GPU acceleration using CUDA
* Distributed computing (MPI)
* Large-scale dataset benchmarking
* Dynamic load balancing
* Visualization dashboard for performance metrics

---

## 👨‍💻 Author

Manshi Singh
B.Tech IT @ IIEST Shibpur
💼 Aspiring SDE | MERN Developer | DSA Enthusiast

⭐ If you found this project useful, consider starring the repository!
