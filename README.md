This repository implements optimization algorithms for transforming two-qubit quantum states using local operations, with a focus on entanglement purification. The code demonstrates how to optimize local quantum channels to prepare target states and maximize fidelity 


# Optimizing Quantum State Transformation Under Locality Constraint

This repository contains a numerical framework for **deterministic and probabilistic bipartite quantum state transformations under locality constraints**, using **gradient-based optimization on a complex Stiefel manifold** to construct optimized local quantum channels.

---

## Abstract

In this paper, we present a general numerical framework for both deterministic and probabilistic quantum state transformations, under locality constraints. For a given arbitrary bipartite initial state and a desired bipartite target state, we construct an optimized local quantum channel that transforms the initial state into the target state with high fidelity. To achieve this goal, local quantum channels are parametrized on a complex Stiefel manifold and optimized using gradient-based methods. We demonstrate that this approach significantly enhances entanglement distillation for weakly entangled states via two complementary strategies: optimized local state transformation and probabilistic local transformation. These results establish our method as a powerful and versatile tool for a broad class of quantum information processing tasks.

---

## Project Initialization

### 1) Create and activate a virtual environment

```bash
python -m venv .venv
source .venv/bin/activate   # macOS/Linux
# .venv\Scripts\activate    # Windows (PowerShell)
```
### 2) Install dependencies
```bash
pip install -r requirements.txt
```
