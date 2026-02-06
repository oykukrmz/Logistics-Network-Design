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
    *  **Binary Decisions ($Y_i$):** 1 if office is open, 0 otherwise.
    * **Capacity:** Maximum annual trips per consultant.
    * **Demand Satisfaction:** All client state demands must be met.
    **"Big M" Method:** Used to link binary decision variables with continuous flow variables.
* **Scenarios Analyzed:**
    *  **(a) Unrestricted Optimization:** Identifying the global optimum (Result: Opening only the **Denver** office minimized the total cost to $219,500).
    *  **(b) Resource Constrained:** Impact of limiting staff size and travel rights.
    * **(c) Single Sourcing:** Enforcing a policy where each state is served by exactly one office.

### Case 2: Global Supply Chain Network Design (M&A Scenario)
* **Objective:** Optimize the production and distribution network for two merging mobile phone manufacturers (**Sleekfon & Sturdyfon**) to serve global markets (NA, SA, EU, Asia, Africa).
* **Key Factors:**
    *  **Cost Structure:** Production costs + Transportation costs + **Import Duties (25%)**.
    * **Merger Analysis:** Evaluating network synergy by comparing "Separate Operations" vs. "Merged Operations".
* **Scenarios Analyzed:**
    *  **(a) As-Is Analysis:** Optimizing separate networks for both companies.
    * **(b) Pooled Capacity:** Combining facilities and demands without closing plants.
    * **(c) Network Rationalization:** Using binary variables to decide which plants should remain open or close after the merger to maximize efficiency.

## 🛠️ Methodology & Tools
*  **Solver Engine:** Simplex LP (Linear Programming).
* **Modeling Techniques:**
    * **Binary Integer Programming:** For Yes/No decisions (Open/Close facility).
    * **Constraint Management:** Modeling capacity, demand, and flow conservation constraints.
    *  **Cost Matrix:** Using `SUMPRODUCT` functions to calculate weighted costs across the network.

## 📊 Key Takeaways
* Successfully modeled a **Multi-Echelon Supply Chain** considering international tariffs and capacity limitations.
* Demonstrated how **Binary Variables** allow for flexible capacity planning compared to rigid models.
* The analysis highlighted the trade-offs between fixed facility costs and variable transportation costs.

## 📄 Files in this Repository
* `Logistics_Optimization_Model.xlsx`: The Excel file containing the Solver parameters, decision variables, and sensitivity analysis.
* `IE363_Logistics_Homework_Solution.pdf`: Detailed project report explaining the mathematical formulation and results.

---
**Author:** [Öykü Kırmızı& group friends]
