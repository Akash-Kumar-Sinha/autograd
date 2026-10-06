# Autograd

A simple scalar-valued automatic differentiation engine built from scratch in Python to understand how autograd works under the hood.

## What's Implemented

- **Autograd Engine**: Tracks operations dynamically and computes gradients using reverse-mode autodiff (backpropagation over a DAG).
- **Core Operations**: Addition, subtraction, multiplication, power, and activations (`relu`, `tanh`).
- **Neural Network Basics**: Minimal implementations of `Neuron`, `Layer`, and `MLP`.

## Reference

- [Overview of PyTorch Autograd Engine](https://pytorch.org/blog/overview-of-pytorch-autograd-engine/)
