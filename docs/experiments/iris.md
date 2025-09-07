---
title: Iris Baseline
parent: Experiments
nav_order: 1
---

# Iris Baseline

## Dataset
- 150 samples, 4 numeric features, 3 classes (Iris-setosa, Iris-versicolor, Iris-virginica).
- File: `data/iris.csv` (with header).

## Goal
- Train a small MLP (1 hidden layer) to reach ≥ 95% test accuracy.

## Plan
- Standardize features using **train-only** statistics (avoid leakage).
- Architecture idea: `4 -> 8..16 -> 3` with softmax + cross-entropy.
- Optimizer: start with vanilla SGD; tune learning rate.

## Results
- _To be filled._

## Notes
- _To be filled._
