---
layout: post
comments: False
date: 20210213
title: Quantum Computing
status: in-progress
---

[[Computer Science]] [[Math]] [[physics]]

## Prerequisites
* [[1-Vectors & Matrices]]
* [[1-Complex Numbers & Complex Exponentials]]
* [[pands]]
# 1- Quantum Computing
{{{{{{{{{{Later}}}}}}}}}}



# Quantum Properites that enhance the computing task
![[Pasted image 20210205183033.png]]


 ## [[2-Quantum Superposition]]
#### Superposition is the property of quantum object where the can be in two states in the same time(the cat is dead and alive )
#### and it is one of the most important property of Quantum Computing which will enhance the computing task
<br>

## [[3-Quantum Entanglement]]
#### Quantum Correlation between q object where the quantum state of an object will depend on another regardless of how far apart they are, and vice versa.
<br>

## [[4-Quantum Interference]]
#### where two Q obejcts will interact with each other and either cancel each other or amplify one another, same as we see in waves.

<br>


# Quantum Bits{not Completed X}
![[Pasted image 20210205183519.png]]
* Classical Bits: 0, 1(off, on)
* Quantum Bits: $\left|0\right>, \left|1\right>$
* ket notaiton( $\left|n\right>$ ): ket notation is the thing that indicate that we are talking in quantum not classical 
* bra notation($\left<n\right|$){{{{{{{{{{Later}}}}}}}}}}
* $\left|0\right> = \begin{pmatrix} 1 \\ 0 \end{pmatrix}, \left|1\right> = \begin{pmatrix} 0 \\ 1 \end{pmatrix}$
 * bra$\left<0\right| = \begin{pmatrix} 1 & 0 \end{pmatrix}, \left<1\right| = \begin{pmatrix} 0 & 1 \end{pmatrix}$

<br>


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

## CNOT Gate
![[Pasted image 20210206195745.png]]
if the control qubit is 0, does nothing
if the control qubit is 1, flip the target qubit

Truth Table

| input | Output |
| --- | ----------- |
| 0,0 | 0,0 |
| 0,1 | 0,1 |
| 1,0 | 1,1 |
| 1,1 | 1,0 |

### Applying Quantum Gates
[[5-Quantum Gates#Applying Quantum gates]]


### [^Applying Quantum gates]





# Why Quantum Computers Faster?

![[Pasted image 20210206194547.png]]
n Qubits $\rightarrow 2^{n}$ Superposition states
Each operation acts on all the elements of the superposition


## What is Quantum Supermacy?
A programmable Quantum Device can solve a problem that
no classical computer can solve in any feasible amount of time

# Two Qubits
$\left|00\right>$  or  $\left|0\right>\left|0\right>$: qubit A is $\left|0\right>$ and qubit B is$\left|0\right>$
$\left|01\right>$  or  $\left|0\right>\left|1\right>$: qubit A is $\left|0\right>$ and qubit B is$\left|1\right>$
$\left|10\right>$  or  $\left|1\right>\left|0\right>$: qubit A is $\left|1\right>$ and qubit B is$\left|0\right>$
$\left|11\right>$  or  $\left|1\right>\left|1\right>$: qubit A is $\left|1\right>$ and qubit B is$\left|1\right>$


<br>
<br>
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
# two level systems

## example:
#### Qubits
#### Electron spin

two level system vs. three level system
![[Pasted image 20210124220616.png]]
4 level system = 2 qubits

## (stern-gerlach experiment)



![[Pasted image 20210124222711.png]]