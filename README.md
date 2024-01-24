# displayPointSets

Implement the following transformations, and use them to transform the shape given by the point set (i.e., fish). 

### Scaling

$$
\begin{align}
	S =
	\begin{bmatrix}
		s_x & 0 \\
		0 & s_y
	\end{bmatrix}.
\end{align}
$$

### Rotation

$$
\begin{align}
	R =
	\begin{bmatrix}
		\cos\theta & -\sin\theta \\
		\sin\theta &  \cos\theta
	\end{bmatrix}.
\end{align}
$$

### Horizontal shear

$$
\begin{align}
	H =
	\begin{bmatrix}
		1 & k \\
		0 &  1
	\end{bmatrix}.
\end{align}
$$



In your code (Jupyter notebook), call the transformation matrices by the same letters used in the above equations, i.e., `S`, `R`, and `H`. Also, the matrix containing the coordinates of the vertices of the original shape should be named `X` and the matrix of the transformed shape should be named `Y`. 

Generate a plot for each transformation showing the original shape and the transformed shape (see example in starter code).

In this assignment, you must code the transformation functions (do not use library functions for the transformations). You can use functions for matrix multiplication from linear algebra libraries or the multiplication operator `@`. 



