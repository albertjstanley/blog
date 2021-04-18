# Linear Algebra Notes

Question: What is the definition of the centered data matrix and the sample covariance matrix?

Answer: 

The centered data matrix is formed by taking the matrix containing the data, determining the "average vector" and subtracting this vector from every column in the original data matrix. It is represented mathematically below: 
$$
\newcommand{\CDM}{ \tilde{X} } \\
\tilde{X} = [\begin{matrix} x_1 & ...& x_n \end{matrix}] \in{R^{d x n}}  \\
x_j  = x_j - \overline{x} \\
\overline{x} = \frac{1}{n} \sum_{j = 1}^{n} x_j
$$

Sample covariance matrix is formed by multiplying the centered data matrix with its transpose and dividing by the number of columns: 

$$
S = \frac{1}{n} \tilde{X}\tilde{X}^T
$$