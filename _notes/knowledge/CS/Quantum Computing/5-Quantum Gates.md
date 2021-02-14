---
layout: post
comments: False
date: 20210210
title: Quantum Gates
status: in-progress
---

# Quantum Gates
Quantum Gates used to make Quantum Computations same as classical computing(bits and gates= Everything)
but quantum gates must be reversible.
## Pauli-X(X-gate)
X(or $\sigma^{2}$ ): Flips the bit
$X(\left|0\right>) \rightarrow \left|1\right>$ 
$X(\left|1\right>) \rightarrow \left|0\right>$ 
matrix:$\begin{bmatrix}0 & 1\\1 & 0\end{bmatrix}$
## Pauli-Z (Z-gate)
Z(or $\sigma^{z}$ ): Phase Gate
$Z(\left|0\right>) \rightarrow \left|0\right>$ 
$Z(\left|1\right>) \rightarrow \left|-1\right>$ 
matrix:$\begin{bmatrix}1 & 0\\0 & -1\end{bmatrix}$
 
 ## Hadamard(H)
 Creates a 50-50 Superposition From $\left|0\right>$ and $\left|1\right>$
$H(\left|0\right>) \rightarrow \frac{\sqrt{0.5}\left|0\right> + \sqrt{0.5}\left|1\right>}{\sqrt{2}}$
$H(\left|1\right>) \rightarrow \frac{\sqrt{0.5}\left|0\right> - \sqrt{0.5}\left|1\right>}{\sqrt{2}}$
matrix:$\frac{1}{\sqrt{2}}\begin{bmatrix}1 & 1\\1 & -1\end{bmatrix}$

# Applying Quantum gates
we can apply Quantum Gates in Two ways
* separately

* in parallel


$X(\left|0\right>) \rightarrow \left|1\right>$ 
$X(\left|1\right>) \rightarrow \left|0\right>$ 
$X\left|ψ\right> = X(α\left|0\right> + β\left|1\right>)$
$=α(X\left|0\right>) + β(X\left|1\right>)$
$=α\left|1\right> + β\left|0\right>$

Example
$Z(\frac{\left|0\right> + \left|1\right>}{\sqrt{2}})$
$=\frac{Z\left|0\right> + Z\left|1\right>}{\sqrt{2}}$
$=\frac{\left|0\right> - \left|1\right>}{\sqrt{2}}$


![[500px-Quantum_Logic_Gates 1.png]]