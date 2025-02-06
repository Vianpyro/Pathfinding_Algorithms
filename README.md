# Pathfinding_Algorithms

## 📌 Description

This project implements and compares three pathfinding algorithms:

- **Breadth-First Search (BFS)**: breadth-first exploration.
- **A-Star Search (A*)**: informed search using Euclidean distance as a heuristic.
- **Hill-Climbing**: optimized local search.

The objective is to analyze their performance on different obstacle configurations.

---

## 📂 Project Structure

```
Pathfinding_Algorithms/
│── main.py                 # Main entry point of the program
│── algorithms/
│   │── bfs.py              # BFS implementation
│   │── astar.py            # A* implementation
│   │── hill_climbing.py    # Hill Climbing implementation
│── utils/
│   │── graph.py            # Graph representation and state management
│   │── heuristics.py       # Heuristic functions for A*
│── tests/
│   │── test_algorithms.py  # Performance testing and comparison
│── README.md               # Project documentation
```

---

## 🚀 Installation and Execution

### 1️⃣ Prerequisites

Ensure that **Python 3.x** is installed on your machine.

### 2️⃣ Installation

Clone this repository and navigate to the folder:

```bash
git clone https://github.com/your-username/Pathfinding_Algorithms.git
cd Pathfinding_Algorithms
```

### 3️⃣ Execution

Run the main program:

```bash
python main.py
```

You will then be able to choose the algorithm to execute and visualize the results.

---

## 📊 Performance Analysis

The algorithms will be compared based on:

- 📌 **Number of explored nodes**
- ⏳ **Computation time**
- 🎯 **Solution quality (optimality)**

Tests are available in `tests/test_algorithms.py`.

---

## 🛠 Possible Improvements

- Add graphical visualization of searches.
- Test other heuristics for A*.
- Optimize the implementation of algorithms.

---

## 📜 License

This project is under the MIT license. You are free to use and modify it.

---

## 📬 Contact

For any questions or suggestions, feel free to open an issue or contact me! 🚀
