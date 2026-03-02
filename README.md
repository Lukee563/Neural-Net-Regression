# Neural-Net-Regression
Feed Forward Neural Network Regression techniques covered in AM230 @ UC Santa Cruz

---

## Table of Contents

### Section 1: Project Setup
- [Feed Forward Neural Net Regression Overview](#feed-forward-neural-net-regression-overview) — Page 1
- [Hidden Layer Optimization Objective](#hidden-layer-optimization-objective) — Page 2

### Section 2: Problem Size in Neural Network Training
- [Deriving Total Trainable Parameters](#deriving-total-trainable-parameters) — Page 3
- [Parameter Growth Function Analysis](#parameter-growth-function-analysis) — Page 3
- [Memory Usage in a "Small" Case](#memory-usage-in-a-small-case) — Page 3
- [Implications for First-Order vs Second-Order Methods](#implications-for-first-order-vs-second-order-methods) — Page 3

### Section 3: Properties of Neural Network Regression
- [Nonconvexity of Neural Network Training](#nonconvexity-of-neural-network-training) — Page 4
- [Hessian and Failure of Positive Semidefiniteness](#hessian-and-failure-of-positive-semidefiniteness) — Page 4
- [Extension to the Empirical Loss](#extension-to-the-empirical-loss) — Page 5

### Section 4: Backpropagation and Gradient Computation
- [Backward Pass Derivation](#backward-pass-derivation) — Page 6
- [Gradient with Respect to Parameters](#gradient-with-respect-to-parameters) — Page 7

### Section 5: Neural Network Training & Initialization
- [Quadratic Regularization](#quadratic-regularization) — Page 8
- [Zero Initialization & Stationary Behavior](#zero-initialization--stationary-behavior) — Page 8
- [Symmetry-Induced Degeneracy Proof](#symmetry-induced-degeneracy-proof) — Page 9
- [Random Initialization Experiments](#random-initialization-experiments) — Page 10
- [Initialization Scale Selection](#initialization-scale-selection) — Page 12

---
