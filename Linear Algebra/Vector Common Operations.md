Vectors have many definitions depending on whether you ask physics, maths or Computer Science teachers. 

Physics teachers will tell you that vectors (unlike scalars - single numbers) have both magnitude and direction. Hence, a car going at 5mph is a scalar whilst a car with velocity (direction and speed) is a vector. Computer science teachers will tell you that vectors are lists. Maths teachers will tell you that we can represent vectors like so. Here's the component form:

$$
\begin{pmatrix}
1 \\ 2 \\ 3
\end{pmatrix}
$$

This can also be represented as:

$$ \mathbb{R}^{3} \in 
\begin{pmatrix}
1 \\ 2 \\ 3
\end{pmatrix}$$

This means that the vector is a real number with 3 dimensions and our vector [1, 2, 3] vector is a member of this.

You might see vectors represented like this:

$$
\vec{a}=
\begin{pmatrix}
1 \\ 2 \\ 3
\end{pmatrix}
$$

You may also see it represented as a bold letter like this:
$$
\bf{x}
$$

## Vector addition / subtraction

A similar approach can be taken with subtraction:

$$
\begin{pmatrix}
1 \\ 2 \\ 3
\end{pmatrix}
-
\begin{pmatrix}
3 \\ 2 \\ 1
\end{pmatrix}
=
\begin{pmatrix}
- 2 \\ 0 \\ 2 
\end{pmatrix}
$$

## Vector multiplication

We can times two vectors together like so:

$$
\begin{pmatrix}
1 \\ 2 \\ 3
\end{pmatrix}
\times
\begin{pmatrix}
2 \\ 3 \\ 4
\end{pmatrix}
= 
\begin{pmatrix}
2 \\ 6 \\ 12
\end{pmatrix}
$$
We simply take each row and times it by the corresponding row of the other vector.

We can also multiply by a scalar:

$$
\begin{pmatrix}
1 \\ 2 \\ 3 
\end{pmatrix}
\times
3
=
\begin{pmatrix}
3 \\ 6 \\ 9
\end{pmatrix}
$$