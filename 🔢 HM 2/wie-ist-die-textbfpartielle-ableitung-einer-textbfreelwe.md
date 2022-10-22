# Note
```
guid: J[jsU/>3)6
notetype: LaTeX-deb4a
```

### Tags
```
18_partielle_integration
wichtig
```

## Front
Wie ist die \textbf{partielle Ableitung einer \textbf{reelwertigen Funktion} $f$ in $x_0$ nach $x_i$} definiert?

## Back
Es sei $x_{0}=\left(\xi_{1}, \ldots, \xi_{n}\right) \in D$ und $i \in\{1, \ldots, n\} .$ Weiter bezeichne
\[
e_{i}=(0, \ldots, 0,1,0, \ldots, 0)
\]
den i-ten Einheitsvektor. Dann gilt
\[
x_{0}+t e_{i}=\left(\xi_{1}, \ldots, \xi_{i-1}, \xi_{i}+t, \xi_{i+1}, \ldots, \xi_{n}\right).
\]
f heißt in $x_{0}$ partiell differenzierbar (pdb) nach $x_{i}: \Longleftrightarrow$ Es existiert der Grenzwert
\[
f_{x_{i}}\left(x_{0}\right):=\frac{\partial f}{\partial x_{i}}\left(x_{0}\right):=\lim _{t \rightarrow 0} \frac{f\left(x_{0}+t e_{i}\right)-f\left(x_{0}\right)}{t} \in \mathbb{R}.
\]
In diesem Fall heißt $f_{x_{i}}\left(x_{0}\right)$ die partielle Ableitung von $f$ in $x_{0}$ nach $x_{i}$.\\<div>
</div><div>\textbf{Beispiel:}\\</div><div>\[
f(x, y)=\left\{\begin{array}{ll}
\frac{x y}{x^{2}+y^{2}}, & \text { für }(x, y) \neq(0,0) \\
0, & \text { für }(x, y)=(0,0)
\end{array} . \text { Wir betrachten } x_{0}=(0,0)\right.
\]
Es gilt $x_{0}+t e_{1}=(t, 0)$
\[
\frac{f\left(x_{0}+t e_{1}\right)-f\left(x_{0}\right)}{t}=\frac{f(t, 0)-f(0,0)}{t}=0 \rightarrow 0 \quad(t \rightarrow 0)
\]
Somit ist $f$ in (0,0) partiell differenzierbar nach $x$ und $f_{x}(0,0)=0$.
</div>
