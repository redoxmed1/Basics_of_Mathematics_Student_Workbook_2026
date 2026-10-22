### Exercise 12. Powers and induction

Given

$$
A=
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
$$

$$
A^2=
\begin{pmatrix}
1 & 2 \\
0 & 1 \\
\end{pmatrix},
\qquad
A^3=
\begin{pmatrix}
1 & 3 \\
0 & 1 \\
\end{pmatrix},
\qquad
A^4=
\begin{pmatrix}
1 & 4 \\
0 & 1 \\
\end{pmatrix}
$$

The conjectured formula is

$$
A^n=
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
$$

For induction, it holds for $n=1$. If it holds for $n$, then

$$
A^{n+1}=A^nA=
\begin{pmatrix}
1 & n \\
0 & 1 \\
\end{pmatrix}
\begin{pmatrix}
1 & 1 \\
0 & 1 \\
\end{pmatrix}
=
\begin{pmatrix}
1 & n+1 \\
0 & 1 \\
\end{pmatrix}
$$

Thus the formula holds for all positive integers $n$.