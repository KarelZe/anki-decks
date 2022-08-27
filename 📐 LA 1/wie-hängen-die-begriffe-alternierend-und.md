## Note
nid: 1582282303760
model: LaTeX-deb4a
tags: Determinante
markdown: false

### Front
Wie hängen die Begriffe alternierend und schiefsymmetrisch zusammen?

### Back
% hier etwas nachlesen <a href="https://de.wikipedia.org/wiki/Determinantenfunktion">https://de.wikipedia.org/wiki/Determinantenfunktion</a><div>
</div><div>Jede alternierende $k$ -lineare Abbildung $D$ ist schief-symmetrisch, denn für $1 \leq i<j \leq k$ und $v_{1}, \ldots, v_{k} \in V$ gilt
$$
\begin{aligned}
0 &=D\left(v_{1}, \ldots, v_{i}+v_{j}, \ldots, v_{i}+v_{j}, \ldots, v_{k}\right) \\
&=D\left(v_{1}, \ldots, v_{i}, \ldots, v_{i}+v_{j}, \ldots, v_{k}\right)+D\left(v_{1}, \ldots, v_{j}, \ldots, v_{i}+v_{j}, \ldots, v_{k}\right) \\
&=D\left(v_{1}, \ldots, v_{i}, \ldots, v_{i}, \ldots, v_{k}\right)+D\left(v_{1}, \ldots, v_{i}, \ldots, v_{j}, \ldots, v_{k}\right) \\
&+D\left(v_{1}, \ldots, v_{j}, \ldots, v_{i}, \ldots, v_{k}\right)+D\left(v_{1}, \ldots, v_{j}, \ldots, v_{j}, \ldots, v_{k}\right) \\
&=D\left(v_{1}, \ldots, v_{i}, \ldots, v_{j}, \ldots, v_{k}\right)+D\left(v_{1}, \ldots, v_{j}, \ldots, v_{i}, \ldots, v_{k}\right)
\end{aligned}
$$
Ist umgekehrt $D$ eine schief-symmetrische $k$ -lineare Abbildung und sind $v_{1}, \ldots, v_{k} \in V$ mit $v_{i}=$
$v_{j}$ für $1 \leq i<j \leq k,$ so gilt
$$
2 \cdot D\left(v_{1}, \dots, v_{i}, \dots, v_{j}, \dots, v_{k}\right)=D\left(v_{1}, \dots, v_{i}, \dots, v_{j}, \dots, v_{k}\right)+D\left(v_{1}, \dots, v_{j}, \dots, v_{i}, \dots, v_{k}\right)=0
$$
</div>
