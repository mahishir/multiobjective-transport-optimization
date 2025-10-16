# Multi-Objective Optimization for Balancing Efficiency and Equity in Urban Transport

This repository contains a conceptual and computational study on designing an **optimization framework** that balances **efficiency** and **equity** in urban transport resource allocation.  
The model provides a foundation for sustainable and fair transport planning.

---

## 🚀 Project Overview
Urban transportation systems often prioritize efficiency—minimizing travel time and congestion—while ignoring fairness in resource distribution.  
This research introduces a **multi-objective optimization model** that integrates both efficiency (total travel time) and equity (fairness among different zones or groups).

---

## 🧩 Objectives
- Develop a simplified transport optimization model.  
- Minimize total system travel time while maintaining equitable resource allocation.  
- Demonstrate how optimization can guide transport policy design.  
- Provide a foundation for further real-world studies (e.g., using data from Kandy, Sri Lanka).

---

## 🧮 Methodology
The project applies a **multi-objective optimization** approach using Python (NumPy, SciPy, Matplotlib).  
- **Efficiency Objective:** Minimize total travel time.  
- **Equity Objective:** Minimize variance among zone travel times.  
- **Solution Method:** Weighted-sum scalarization to explore trade-offs.  
- **Simulation Data:** Synthetic data used for demonstration.

---

## 📊 Results (Example)
| Zone | Base Travel Time | Optimized Vehicles | Travel Time |
|------|------------------|--------------------|--------------|
| Zone 1 | 25 | 22.82 | 11.68 |
| Zone 2 | 30 | 17.96 | 15.81 |
| Zone 3 | 35 | 22.82 | 16.35 |
| Zone 4 | 40 | 17.38 | 21.40 |
| Zone 5 | 45 | 12.58 | 27.63 |
| Zone 6 | 50 | 6.45 | 37.81 |

These results demonstrate how the allocation of transport resources can significantly reduce overall travel time while balancing between different city zones.

---

## 🧰 Tools and Libraries
- Python 3  
- NumPy  
- Matplotlib  
- SciPy  

---

## ⚙️ How to Run
1. Open `multiobjective_transport_optimization.ipynb` in **Google Colab** or **Jupyter Notebook**.  
2. Run all cells sequentially.  
3. Modify weights or parameters to explore different trade-offs between efficiency and equity.

---

## 📚 References
1. Yang, H., & Bell, M. G. H. (1998). Models and algorithms for road network design: a review and some new developments. *Transport Reviews*, 18(3), 257–278.  
2. Rawls, J. (1971). *A Theory of Justice*. Harvard University Press.  
3. Cervero, R. (1998). *The Transit Metropolis: A Global Inquiry*. Island Press.  
4. Pereira, R. H., & Banister, D. (2021). Distributive justice and transportation equity: A comparative review. *Transport Reviews*, 41(2), 142–162.

---

## 🌍 Future Work
- Apply the model to **real-world data from Kandy, Sri Lanka**.  
- Integrate **machine learning** to predict traffic patterns.  
- Extend to **multi-modal transport systems** (buses, trains, etc.).

---

## 👩‍💻 Author
**Mahishi Rajaguru**  
Graduate Researcher in Financial & Industrial Mathematics  
📍 Uppsala University, Sweden  
📧 mahishiraja90@gmail.com  

