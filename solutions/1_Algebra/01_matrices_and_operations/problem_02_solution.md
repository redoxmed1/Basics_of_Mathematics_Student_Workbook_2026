### Exercise 2. Matrix addition and scalar multiplication

## Question

Given

$$
A=
\begin{pmatrix}
1 & 2 \\
-1 & 3
\end{pmatrix},
\qquad
B=
\begin{pmatrix}
4 & -2 \\
0 & 5
\end{pmatrix},
$$

calculate \(A+B\), \(A-B\), and \(3A-2B\).

## Solution

Both matrices are \(2\times2\), so corresponding entries have the same row and column indices. Matrix addition and subtraction are performed entry by entry. The matrices must have the same dimensions; otherwise, there is no matching entry at every position.

### 1. Addition

Add entries in matching positions:

$$
A+B=
\begin{pmatrix}
1+4 & 2+(-2) \\
-1+0 & 3+5
\end{pmatrix}
=
\begin{pmatrix}
5 & 0 \\
-1 & 8
\end{pmatrix}.
$$

### 2. Subtraction

Subtract each entry of \(B\) from the corresponding entry of \(A\):

$$
A-B=
\begin{pmatrix}
1-4 & 2-(-2) \\
-1-0 & 3-5
\end{pmatrix}
=
\begin{pmatrix}
-3 & 4 \\
-1 & -2
\end{pmatrix}.
$$

### 3. Scalar multiplication and subtraction

First multiply every entry of \(A\) by 3 and every entry of \(B\) by 2:

$$
3A=
\begin{pmatrix}
3 & 6 \\
-3 & 9
\end{pmatrix},
\qquad
2B=
\begin{pmatrix}
8 & -4 \\
0 & 10
\end{pmatrix}.
$$

Now subtract the matching entries of \(2B\) from \(3A\):

$$
3A-2B=
\begin{pmatrix}
3-8 & 6-(-4) \\
-3-0 & 9-10
\end{pmatrix}
=
\begin{pmatrix}
-5 & 10 \\
-3 & -1
\end{pmatrix}.
$$
