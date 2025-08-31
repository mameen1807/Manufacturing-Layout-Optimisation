# Manufacturing Layout Optimisation

## 📌 Overview
This project demonstrates **manufacturing layout optimisation** using:
- **Discrete-Event Simulation (DES)** to model product flow across workstations.
- **Simulated Annealing** as a search heuristic to find better layouts.
- **Performance evaluation** through average completion time of jobs.

This approach shows how optimising the sequence of workstations can reduce production time and improve efficiency.

## 🎯 Objectives
- Model a simple **manufacturing line** with stations (A, B, C).
- Measure **average completion time** for different layouts.
- Use **simulated annealing** to discover an improved layout.
- Compare performance before and after optimisation.

## 🛠️ Methodology
1. Define workstations with **random processing times**.
2. Simulate job flow using **SimPy** (discrete-event simulation).
3. Run the process for multiple jobs and compute **average time**.
4. Apply **simulated annealing** to explore layout permutations.
5. Identify the layout with **minimum expected completion time**.

## 📊 Key Results
- The **initial layout** (A → B → C) had an average completion time of ~20.6 units.
- The **optimised layout** (B → A → C) reduced the average completion time to ~18.5 units.
- This shows a **~10% improvement** in efficiency.

## 📷 Example Output
![Optimisation Progress](layout_optimisation_progress.png)

## 🚀 How to Run
```bash
python manufacturing_layout_optimisation.py
