Linear combinations allow us to build new vectors from existing ones. We can take a given vector and multiply it by a scalar such that:

Consider a set of vectors v1, v2, ..., vn in a vector space. A linear combination of these vectors is any vector of the form "a1v1 + a2v2 + ... + an*vn", where a1, a2, ..., an are scalars (real or complex numbers).

We can create any vector from a combination of two vectors (provided that they are not colinear) by multiplying them by some scalar. This means that:

$$
c_{1}\vec{a}+c_{2}\vec{b}=\vec{c}
$$
Let's look at this more concretely:
$$
c_1\begin{pmatrix}
1 \\ 2
\end{pmatrix}
+
c2\begin{pmatrix}
2 \\ 3
\end{pmatrix}
= 
\begin{pmatrix}
4 \\ 6
\end{pmatrix}
$$
There is some value of c1 and c2 that we use here to create this combination. Let's break it down further:

$$
\begin{align}
c_{1}1 + c_{2}2 = 4
\\
c_12 + c_23 = 6
\end{align}
$$

We can also write this as:

$$
\begin{align}
x+2y = 4
\\
2x+3y = 6
\end{align}
$$

We can times the first equation by 2 and then apply extraction:

$$
\begin{align}
2x+4y = 8
\\
2x+3y = 6
\end{align}
$$
Subtract the first equation from the second:

$$
\begin{align}
y = 2
\end{align}
$$
Substituting into our first equation then results in:

$$
\begin{align}
x+4 = 4
\end{align}
$$
Which means x is 0. If x is 0 then these are not co-linear.

## Span

Span means all the possible linear combinations of that vector or set of vectors. If you have two vectors (that are not co-linear - meaning that they are not on the same line) then they can span the entire plane (all of 2D space).

As we showed above, we can take two vectors that are not co-linear and by scaling by some x,y value we can get any point anywhere. That means in practice the span is the entirety of R2.

### Linear Dependence

Vectors that are co-linear are said to be linearly dependent. We can see this because our equation above will never allow us to find a vector that is on a different line if the vectors are co-linear. For example:

$$
c_1
\begin{pmatrix}
2 \\ 3
\end{pmatrix}
+
c_2
\begin{pmatrix}
4 \\ 6
\end{pmatrix}
$$
There are no values of c1 and c2 that will allow to span all of R2 because these values lie on the same line. We can see that adding these the first vector to the other which will just result in a value along the same line since these two values are co-linear. 

https://www.khanacademy.org/math/linear-algebra/vectors-and-spaces/linear-combinations/v/linear-combinations-and-span