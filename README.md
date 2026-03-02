# Neural-Net-Regression

Feed Forward Neural Network Regression techniques developed in **AM230: Numerical Optimization Methods**   

---

## 📄 Project Overview

This project studies the theoretical and computational properties of **feedforward neural network regression** from an optimization perspective.

We construct and analyze fully-connected neural networks and investigate:

- Parameter growth and scaling behavior  
- Memory constraints in high dimensions  
- Nonconvexity of the training objective  
- Backpropagation derivations  
- Initialization pathologies and symmetry-induced degeneracy  
- First-order vs second-order optimization feasibility  

The emphasis is on rigorous mathematical derivation combined with numerical experimentation.

---

## Table of Contents

### 1. Project Setup
- Input–Output Regression Framework  
- Feedforward Neural Network Architecture  
- Hidden Layer Optimization Objective  

### 2. Problem Size in Neural Network Training
- Derivation of Total Trainable Parameters  
- Scaling with Width (m) and Depth (n)  
- Memory Requirements (O(P) vs O(P²))  
- Implications for First-Order vs Second-Order Methods  

### 3. Theoretical Properties
- Proof of Nonconvexity  
- Hessian Structure and Indefiniteness  
- Extension to the Empirical Risk  

### 4. Backpropagation
- Forward Pass Formulation  
- Recursive Sensitivity Derivation  
- Gradient Computation via Chain Rule  

### 5. Initialization & Optimization Behavior
- Quadratic Regularization  
- Zero Initialization and Stationary Points  
- Symmetry-Induced Degeneracy (Inductive Proof)  
- Random Initialization Experiments  
- Initialization Scale and Vanishing Gradients  

---

## Numerical Experiments

Experiments were implemented in MATLAB and include:

- Two-hidden-layer neural network regression  
- Line search gradient descent  
- Zero vs Gaussian initialization comparisons  
- RMSE / MAE evaluation  
- Residual distribution analysis  

---

## Key Takeaways

- Neural network training is fundamentally **nonconvex**.
- Width drives parameter growth quadratically.
- Full Hessian storage becomes infeasible at realistic scales.
- Zero initialization creates symmetry-induced degeneracy.
- Initialization scale directly affects gradient propagation.

---

## Tools

- MATLAB
- First-order optimization methods
- Analytical derivations (chain rule, Hessian analysis)

---
