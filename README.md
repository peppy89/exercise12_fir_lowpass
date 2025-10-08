# Exercise 12 – FIR Low-Pass Filter Design

## Overview
This project designs and analyzes a **Low-Pass FIR filter** using the **direct formula** for the impulse response:

\[
h_{LP}(n) = \frac{\sin \big( \omega_c (n - M/2) \big)}{\pi \, (n - M/2)}
\]

with the special case at the center:
\[
h_{LP}(M/2) = \omega_c / \pi
\]

We compare filters of order **M = 20** and **M = 64** to study the effect of filter length on the frequency response.

---
