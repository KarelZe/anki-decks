## Note
nid: 1589226713902
model: LaTeX
tags: 18_partielle_integration, wichtig
markdown: false

### Front
Wann heißt eine reelwertige Funktion $f$ mit $f: D \rightarrow \mathbb{R}$, wobei $D \subseteq \mathbb{R}^{n}$ in $x_0$ \textbf{differenzierbar}?

### Back
$f$ heißt in $x_{0} \in D$ differenzierbar $(d b): \Longleftrightarrow$
\[
\begin{array}{l}
\quad \exists a \in \mathbb{R}^{n}: \lim _{h \rightarrow 0} \frac{f\left(x_{0}+h\right)-f\left(x_{0}\right)-a \cdot h}{\|h\|}=0 \\
\Longleftrightarrow \exists a \in \mathbb{R}^{n}: \lim _{x \rightarrow x_{0}} \frac{f(x)-f\left(x_{0}\right)-a \cdot\left(x-x_{0}\right)}{\left\|x-x_{0}\right\|}=0
\end{array}
\]
wobei "$\cdot$" das Skalarprodukt bezeichnet.
