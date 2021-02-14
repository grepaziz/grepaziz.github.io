
# Vectors
### Vector is something have magnitude and direction, it's always in 2d or 3d but it can be more!!
![Image result for vector math](http://jccc-mpg.wdfiles.com/local--files/vectors/Vector.jpg)

<br>


## Vector representaiton 
## $\vec{v} = \begin{pmatrix} v_{1}\\ v_{2}\\ \vdots  \\ v_{n}\end{pmatrix}\\$

<br>

## Vector Shape
## $(m X n)$ or (Rows, Columns)
## Column Vector
### $\vec{v} = \begin{pmatrix} v_{1}\\ v_{2}\\ \vdots  \\ v_{n}\end{pmatrix}\\$
## Row Vector
### $\vec{v} = \begin{pmatrix} v_{1}\ v_{2}\ \dots  \ v_{n}\end{pmatrix}\\$
<br>

## Vector direction in 2d: 
## $\angle \vec{v} = tan^{-1} (\frac{v_{y}}{v_{x}})$

<br>

## Vector Magnitude:
## $\left \| \vec{v} \right \| = \sqrt{v_{1}^{2} + v_{2}^{2} +\cdots + v_{n}^{2}}$ 
## same as $\sqrt{\vec{v}\cdot \vec{v}}$ square root of the dot product

<br>

## Vector Addition:
## $\vec{a} + \vec{b} = \begin{pmatrix} a_{1}+b_{1}\\ a_{2}+b_{2}\\ \vdots  \\ a_{n}+b_{n}\end{pmatrix}\\$

<br>

## Vector-Scalar Multiplicaiton:
## $c \ast  \vec{v} = \begin{pmatrix} c \ast  \vec{v_{1}}\\ c \ast  \vec{v_{2}}\\ \vdots  \\ c \ast  \vec{v_{n}}\end{pmatrix}\\$

<br>


# Vectors Products

<br>

## Transpose
### Transpose is he transpose of a matrix is an operator which flips a matrix over its diagonal that is, it switches the row and column indices of the matrix
![](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e4/Matrix_transpose.gif/200px-Matrix_transpose.gif)
#### if $\vec{v} = \begin{pmatrix} v_{1}\\ v_{2}\\ \vdots  \\ v_{n}\end{pmatrix}\\$
#### then $\vec{v^{T}} = \begin{pmatrix} v_{1}\ v_{2}\ \dots  \ v_{n}\end{pmatrix}\\$
#### and vice versa

<br>

## Dot Product
### is the way used to multiply a vector with another
## $(\vec{v}\cdot\vec{w}) = \vec{v}\cdot\vec{w^{T}}= \sum_{i=1}^{n}v_{i}w_{i}$
## same as $\sum^{n}_{i=1} \vec{v_{i}}\vec{w_{i}}=  \left \| \vec{v} \right \| \left \| \vec{w} \right \| cos(\theta)$
## Vector orthognality
![[Pasted image 20210213183756.png]]

<br>

## Vector Normalization
A Vector is normalized if it has a magnitude of 1(Unit Vector)
## $\frac{\vec{v}}{\sqrt{(\vec{v}\cdot\vec{v^{T}})}} = \frac{\vec{v}}{\left \| \vec{v} \right \|}$

<br>

## Angle Between Vectors
## $\theta = cos^{-1}(\frac{\vec{x}\cdot\vec{y}}{\left \| \vec{x} \right \| \left \| \vec{y} \right \|})$ 

<br>

# Vectors inner product for Complex Numbers

## Conjugate Transpose
### Conjugate Transpose used when we have complex numbers inside the vector!
### $\vec{v^{\dagger}}=(\vec{v^{T}})^{*}= (\vec{v^{*}})^{T}$

<br>

## The Complex inner proudct(Dot Product)
## $(\vec{v}\cdot\vec{w}) = \vec{v^{\dagger}}\cdot\vec{w^{T}}= \sum_{i=1}^{n}v^{*}_{i}w_{i}$, where $\vec{v},\vec{w} \in C^{n}$
## same as $\sum^{n}_{i=1} \vec{v_{i}^{*}}\vec{w_{i}} = \left \| \vec{v} \right \| \left \| \vec{w} \right \| cos(\theta)$

<br>

# Linear Combinations
#### A linear compination of a set terms is simply the addition of those terms multiplied by scalar coefficients
#### in the case of Vectors, A linear combination is simply a weighted sum of vectors
## $\vec{v} = a_{1}\vec{v_{1}} + a_{2}\vec{v_{3}} + a_{n}\vec{v_{n}} = \sum^{n}_{i=1} a_{i}\vec{v_{i}}$
### in the case of Quantum states, a superposition is simply a linear combination of quantum states

<br>
<br>

# Matrices

