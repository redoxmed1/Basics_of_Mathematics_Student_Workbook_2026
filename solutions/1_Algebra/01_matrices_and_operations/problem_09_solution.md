### Exercise 9. Order of matrix transformations

Given

$$
S=
\begin{pmatrix}
2 & 0 \\
0 & 1 \\
\end{pmatrix},
\qquad
R=
\begin{pmatrix}
0 & -1 \\
1 & 0 \\
\end{pmatrix},
\qquad
x=
\begin{pmatrix}
1 \\
2 \\
\end{pmatrix}
$$

Applying $S$ first and then $R$:

$$
RSx=R
\begin{pmatrix}
2 \\
2 \\
\end{pmatrix}
=
\begin{pmatrix}
-2 \\
2 \\
\end{pmatrix}
$$

Applying $R$ first and then $S$:

$$
SRx=S
\begin{pmatrix}
-2 \\
1 \\
\end{pmatrix}
=
\begin{pmatrix}
-4 \\
1 \\
\end{pmatrix}
$$

Thus $RSx\ne SRx$.