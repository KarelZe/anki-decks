## Note
nid: 1589641510793
model: LaTeX
tags: differentialrechnung_im_R_n, wichtig
markdown: false

### Front
Es sei $f \in C^{2}(D, \mathbb{R})$ und $x_{0} \in D$. Wie ist die \textbf{Hesse-Matrix} definiert?

### Back
Es sei $f \in C^{2}(D, \mathbb{R})$ und $x_{0} \in D$. Die Matrix
\[ H_{f}\left(x_{0}\right):=\left(\begin{array}{cccc} f_{x_{1}
x_{1}}\left(x_{0}\right) & f_{x_{1} x_{2}}\left(x_{0}\right) &
\dots & f_{x_{1} x_{n}}\left(x_{0}\right) \\ \vdots & & & \vdots \\
f_{x_{n} x_{1}}\left(x_{0}\right) & f_{x_{n}
x_{2}}\left(x_{0}\right) & \cdots & f_{x_{n}
x_{n}}\left(x_{0}\right) \end{array}\right) \] heißt
\textit{Hesse-Matrix} von $f$ in $x_{0}$.
<div>
  \textbf{Beispiel:}
</div>
<div>
  Betrachte $f(x, y)=x^{3} y+x y\left((x, y) \in
  \mathbb{R}^{2}\right) .$ Es gilt: \[ \begin{array}{c} f_{x}(x,
  y)=3 x^{2} y+y, f_{y}(x, y)=x^{3}+x \\ f_{x x}(x, y)=6 x y, f_{x
  y}(x, y)=3 x^{2}+1, f_{y y}(x, y)=0 \end{array} \] Damit ist \[
  H_{f}(x, y)=\left(\begin{array}{cc} 6 x y & 3 x^{2}+1 \\ 3
  x^{2}+1 & 0 \end{array}\right). \]
</div>
