# Logistics-Network-Design
Supply Chain Network Design &amp; Facility Location Optimization using Mixed-Integer Linear Programming (MILP) in Excel Solver.
# Logistics Network Design & Facility Location Optimization 🏭🚚

## Project Overview
This project involves solving complex **Facility Location** and **Supply Chain Network Design** problems using **Mixed-Integer Linear Programming (MILP)**. The study was conducted as part of the *IE363 Logistics Management* course.

The primary objective is to minimize total network costs—including fixed facility costs, variable production/transportation costs, and customs duties—while satisfying demand and capacity constraints. The optimization models were built and solved using **Microsoft Excel Solver**.

## 📂 Case Studies

### Case 1: Office Location Problem (Facility Location)
* **Objective:** Determine the optimal set of consulting offices to open among 4 candidate locations (LA, Tulsa, Denver, Seattle) to serve client states at minimum cost.
* **Key Constraints:**
    * [cite_start]**Binary Decisions ($Y_i$):** 1 if office is open, 0 otherwise[cite: 400].
    * **Capacity:** Maximum annual trips per consultant.
    * [cite_start]**Demand Satisfaction:** All client state demands must be met[cite: 404].
    * [cite_start]**"Big M" Method:** Used to link binary decision variables with continuous flow variables.
* **Scenarios Analyzed:**
    * [cite_start]**(a) Unrestricted Optimization:** Identifying the global optimum (Result: Opening only the **Denver** office minimized the total cost to $219,500).
    * [cite_start]**(b) Resource Constrained:** Impact of limiting staff size and travel rights[cite: 447].
    * **(c) Single Sourcing:** Enforcing a policy where each state is served by exactly one office[cite: 467].

### Case 2: Global Supply Chain Network Design (M&A Scenario)
* **Objective:** Optimize the production and distribution network for two merging mobile phone manufacturers (**Sleekfon & Sturdyfon**) to serve global markets (NA, SA, EU, Asia, Africa).
* **Key Factors:**
    * [cite_start]**Cost Structure:** Production costs + Transportation costs + **Import Duties (25%)**.
    * [cite_start]**Merger Analysis:** Evaluating network synergy by comparing "Separate Operations" vs. "Merged Operations"[cite: 471].
* **Scenarios Analyzed:**
    * [cite_start]**(a) As-Is Analysis:** Optimizing separate networks for both companies[cite: 493].
    * [cite_start]**(b) Pooled Capacity:** Combining facilities and demands without closing plants[cite: 614].
    * **(c) Network Rationalization:** Using binary variables to decide which plants should remain open or close after the merger to maximize efficiency[cite: 640].

## 🛠️ Methodology & Tools
* [cite_start]**Solver Engine:** Simplex LP (Linear Programming)[cite: 434, 441].
* **Modeling Techniques:**
    * **Binary Integer Programming:** For Yes/No decisions (Open/Close facility).
    * **Constraint Management:** Modeling capacity, demand, and flow conservation constraints.
    * [cite_start]**Cost Matrix:** Using `SUMPRODUCT` functions to calculate weighted costs across the network[cite: 418].

## 📊 Key Takeaways
* Successfully modeled a **Multi-Echelon Supply Chain** considering international tariffs and capacity limitations.
* Demonstrated how **Binary Variables** allow for flexible capacity planning compared to rigid models.
* The analysis highlighted the trade-offs between fixed facility costs and variable transportation costs.

## 📄 Files in this Repository
* `Logistics_Optimization_Model.xlsx`: The Excel file containing the Solver parameters, decision variables, and sensitivity analysis.
* `IE363_Logistics_Homework_Solution.pdf`: Detailed project report explaining the mathematical formulation and results.

---
**Author:** [Öykü Kırmızı& group friends]
