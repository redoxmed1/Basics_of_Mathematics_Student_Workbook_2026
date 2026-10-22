### Exercise 8. Elementary row operations

Start with

$$
A=
\begin{pmatrix}
1 & 2 & -1 \\
2 & 4 & 1 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

Apply $R_2\leftarrow R_2-2R_1$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
-1 & 1 & 3 \\
\end{pmatrix}
$$

Apply $R_3\leftarrow R_3+R_1$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 0 & 3 \\
0 & 3 & 2 \\
\end{pmatrix}
$$

Swap $R_2$ and $R_3$:

$$
\begin{pmatrix}
1 & 2 & -1 \\
0 & 3 & 2 \\
0 & 0 & 3 \\
\end{pmatrix}
$$

The inverse operations, in reverse order, are: swap $R_2$ and $R_3$, then $R_3\leftarrow R_3-R_1$, then $R_2\leftarrow R_2+2R_1$.