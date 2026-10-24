### Exercise 1. Matrix entries and rows/columns

## Question

Let \(A\) be a \(2\times3\) matrix and \(B\) be a \(3\times2\) matrix, with the following entries and parts:

$$
A=
\begin{pmatrix}
a_{11} & -1 & a_{13} \\
0 & 4 & 5
\end{pmatrix},
\qquad
B=
\begin{pmatrix}
1 & b_{12} \\
-2 & b_{22} \\
4 & 1
\end{pmatrix}.
$$

Find \(a_{12}\), \(a_{23}\), \(b_{21}\), and \(b_{32}\). Also write the second row of \(A\) and the first column of \(B\).

## Solution

The first index in an entry such as \(a_{ij}\) identifies the **row**, and the second index identifies the **column**. Therefore, \(a_{ij}\) is found at row \(i\), column \(j\). Matrix \(A\) has 2 rows and 3 columns, so its size is \(2\times3\); matrix \(B\) has 3 rows and 2 columns, so its size is \(3\times2\).

- \(a_{12}=-1\): row 1, column 2 of \(A\).
- \(a_{23}=5\): row 2, column 3 of \(A\).
- \(b_{21}=-2\): row 2, column 1 of \(B\).
- \(b_{32}=1\): row 3, column 2 of \(B\).

The second row of \(A\) is obtained by reading across row 2:

$$
\begin{pmatrix}
0 & 4 & 5
\end{pmatrix}
$$

The first column of \(B\) is obtained by reading down column 1:

$$
\begin{pmatrix}
1 \\
-2 \\
4
\end{pmatrix}
$$
