---
title: Project Plan
nav_order: 2
parent: Home
---

# Neural Network From Scratch - Project Plan

## 1. Motivation
The goal of this project is to fully understand how neural networks work by **building one from scratch without using external ML libraries**. 
Only the Python standard library will be used.  

By doing this, I want to:
- Understand the math behind forward and backward propagation.
- Learn how optimizers, losses, and activations actually work internally.
- Practice clean project structure and Git/GitHub workflow.

---

## 2. Scope
I will build a simple feed-forward neural network that can:
1. Solve XOR.
2. Classify the Iris dataset.
3. Later: classify Breast Cancer dataset and MNIST (as harder challenges).

---

## 3. Repo Structure
```
nn-from-scratch/
  data/               # datasets (iris.csv, etc.)
  docs/               # notes, math, plan
  src/                # source code
    math/             # basic math ops
    nn/               # layers, activations, loss
    train/            # training loop
  tests/              # unit tests
  experiments/        # experiment setups and results
```

---

## 4. Rules
- No external ML libraries.
- Use only Python standard library.
- Write math derivations before coding.
- Keep commits small and meaningful.
- Document experiments.

---

## 5. Dataset Info
### Iris Dataset
- Source: UCI Machine Learning Repository.
- 150 samples, 4 numeric features, 3 classes.
- Saved locally as `data/iris.csv` with header row.

Future datasets:
- Breast Cancer Wisconsin Diagnostic dataset.
- MNIST.

---

## 6. Expected Outcomes
- Fully working neural net implementation (forward + backprop).
- Experiments proving training works (Iris accuracy ≥ 95%).
- Clear documentation of the math and code structure.
- GitHub repository that shows progress step by step.
