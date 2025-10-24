# Multi-Objective Grey Wolf Optimizer (MOGWO)

> MATLAB implementation of the **Multi-Objective Grey Wolf Optimizer (MOGWO)** — a nature-inspired algorithm for solving multi-criterion optimization problems.

---

Overview

This project provides a **MATLAB implementation** of the **Multi-Objective Grey Wolf Optimizer (MOGWO)**, an extension of the Grey Wolf Optimizer designed to handle **multi-objective optimization problems (MOPs)**.

The MOGWO algorithm is inspired by the **leadership hierarchy** and **hunting mechanism** of grey wolves in nature, adapted for optimization through a balance between exploration and exploitation.



Reference

This implementation is based on the following paper:

> **S. Mirjalili, S. Saremi, S. M. Mirjalili, L. Coelho**  
> *"Multi-objective grey wolf optimizer: A novel algorithm for multi-criterion optimization,"*  
> **Expert Systems with Applications**, Elsevier, 2016.  
> DOI: [10.1016/j.eswa.2015.10.039](https://doi.org/10.1016/j.eswa.2015.10.039)


Implementation Details

- **Programming Language:** MATLAB (Tested on R2011b and above)
- **Algorithm Type:** Multi-Objective Metaheuristic Optimization
- **Inspired By:** Natural behavior of grey wolves (leadership hierarchy & hunting)
- **Core Idea:** Uses three best solutions (Alpha, Beta, Delta) to guide the population
- **Base Algorithm:** Built upon MOPSO (Multi-Objective Particle Swarm Optimization) concepts for repository management and non-dominated sorting.

Algorithm Highlights

- Maintains a repository (archive) of non-dominated (Pareto-optimal) solutions  
- Uses adaptive coefficients to balance exploration/exploitation  
- Applies a grid-based approach for leader selection pressure  
- Supports common CEC’09 benchmark functions (e.g., UF1, UF2, …)  
- Visualizes convergence and Pareto fronts dynamically  


## 📁 Project Structure

