# Runge-Kutta methods for solving initial value problems with MATLAB

## Purpose
This code solves any initial value problem (IVP) of arbitraty order using a Runge Kutta method (RKM) spcified by a Butcher tableau or method name.

## Limitations
Currently, only non-adaptive RKM are supported. Solution algorithms are given for explicit and implicit problems. The latter uses the Newton-Raphson-algorithm to solve the function at every stage of the RKM.
