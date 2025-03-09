"""
# Sign Gradient Descent & Variants

## Overview
This repository contains an analysis of Sign Gradient Descent (SGD) and its adaptive versions.
The research focuses on **optimization efficiency, robustness to noise, and convergence properties**.

## Algorithms Implemented
- **Gradient Descent (GD)**: Standard method using full gradient updates.
- **Sign Gradient Descent (SGD)**: Uses only the sign of the gradient, reducing sensitivity to noise.
- **Adaptive SGD (ASGD)**: Dynamically adjusts step sizes for improved stability.
- **Hybrid Gradient Descent (HGD)**: Combines GD and SGD for better performance.

## Experimental Setup
The algorithms are tested on the following benchmark functions:
1. **Trimodal Function**: f(x) = sin(x) + sin(3x) + sin(5x) + 3
2. **Quadratic Function**: f(x) = x² + 4x + 4
3. **Cubic Function**: f(x) = x³
4. **Quartic Function**: f(x) = x⁴

## Repository Structure
- `/code/` - Python implementations of optimization algorithms
- `/results/` - Experimental data and visualization outputs
- `/docs/` - Research paper and report on findings

## How to Use
### Installation
Ensure Python 3.x and required dependencies are installed.

```bash
pip install -r requirements.txt
