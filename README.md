# Manufacturing-Layout-Optimisation

## 📌 Project Overview
This project demonstrates **Manufacturing Layout Optimisation** using **Discrete-Event Simulation** and **Simulated Annealing**.  

We simulate products moving through a set of workstations (`A`, `B`, `C`), each with a random processing time.  
The goal is to find the **optimal station order (layout)** that minimizes the **average completion time**.  

---

## ⚙️ Technologies Used
- Python
- SimPy (discrete-event simulation)
- NumPy
- Matplotlib

---

## 🚀 How It Works
1. Define a manufacturing process with stations (`A`, `B`, `C`).
2. Simulate the process with a given layout and compute the **average completion time**.
3. Use **Simulated Annealing** to explore different layouts.
4. Select the layout with the **minimum average time**.

---

## 🧩 Code Structure

### 1️⃣ Import Libraries
```python
import simpy
import random
import numpy as np
import matplotlib.pyplot as plt
