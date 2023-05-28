# ESP-QP

[![Component Registry](https://components.espressif.com/components/kirkrudolph/esp-qp/badge.svg)](https://components.espressif.com/components/kirkrudolph/esp-qp)

Port of OSQP embedded Quadratic Program (QP) solver for ESP32. 

> A code generation software package that accepts a parametric description of a quadratic program (QP) as input and generates tailored C code that compiles into a fast and reliable optimization solver for the QP that can run on embedded platforms.

## Use Cases
- Model Predictive Controll (MPC)
- Robust Least-Squares
- Constrained Least-Squares
- Sparse Linear Regression
- Portfolio Optimization
- Support Vector Machines (SVM)

## Getting Started

See the examples folder.

## OSQP References
- [Github](https://github.com/osqp/osqp)
- [Documentation](https://osqp.org/)

```
@article{osqp,
  author  = {Stellato, B. and Banjac, G. and Goulart, P. and Bemporad, A. and Boyd, S.},
  title   = {{OSQP}: an operator splitting solver for quadratic programs},
  journal = {Mathematical Programming Computation},
  year    = {2020},
  volume  = {12},
  number  = {4},
  pages   = {637--672},
  doi     = {10.1007/s12532-020-00179-2},
  url     = {https://doi.org/10.1007/s12532-020-00179-2},
}
```