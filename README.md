# 📊 Math 245: Modeling and Simulation

This repository contains code and documentation from Math 245, focused on mathematical modeling and simulation techniques to analyze real-world systems.

## 🧠 Project Overview

### 🚲 Bikeshare Modeling and Simulation
This project investigates how the number of bikes in a bikeshare system impacts daily revenue. The goal is to find an optimal balance — too few bikes leads to unmet demand, and too many leads to diminishing returns.

We developed a simulation of a 24-hour period for a fictional bikeshare system operating between Olin and Wellesley with the following assumptions:
- Higher probability of renting from Olin to Wellesley (0.09) than vice versa (0.002).
- Even distribution of bikes at both locations (Olin gets the extra if odd).
- Constant rental probabilities throughout the day.
- Uniform bike cost across both locations.

### 📈 Key Insights
- Revenue increases with the number of bikes — up to a point.
- After approximately 250 bikes, the increase in revenue begins to level off, indicating diminishing returns.
- Future simulations could incorporate time-based rental probabilities (e.g., rush hours).

## 🗃 Files Included
- `Project 1 Final.ipynb`: Jupyter Notebook containing the simulation code, charts, and analysis.
- `Project1WriteUp.docx`: Full project report and analysis written by Deveshwar Singh & Kenley Nicholas.

## 📌 Purpose
To use simulation and probabilistic modeling to analyze and predict outcomes in real-world-like systems and support data-driven decision-making.

## ✅ Requirements
- Python 3.x
- Jupyter Notebook
- `matplotlib`, `numpy`

## 🚀 Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Devsingh98/Math-245-Modeling-and-Simulation-.git
   cd Math-245-Modeling-and-Simulation-
   ```

2. Launch the notebook:
   ```bash
   jupyter notebook "Project 1 Final.ipynb"
   ```

3. Run the cells and explore the simulation and its results.

---
