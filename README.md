# Runge-Kutta methods for solving initial value problems with MATLAB

## Purpose
This code solves any **initial value problem (IVP)** of arbitraty order using a **Runge Kutta method (RKM)** spcified by a **Butcher tableau** or method name.

## Limitations
Currently, _only non-adaptive RKM_ are supported. Solution algorithms are given for _explicit_ and _implicit_ problems. The latter uses the **Newton-Raphson-algorithm** to solve the equation at every stage of the RKM.
