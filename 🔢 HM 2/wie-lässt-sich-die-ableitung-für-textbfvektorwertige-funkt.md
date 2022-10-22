# Note
```
guid: s%#6_0nN=j
notetype: LaTeX-deb4a
```

### Tags
```
vektorwertige_funktionen
wichtig
```

## Front
Wie lässt sich die Ableitung für \textbf{vektorwertige Funktionen} im $\mathbb{R}^n$ berechnen?

## Back
% Satz 19.2:
<div>
  Sind alle partiellen Ableitungen $\frac{\partial f_{j}}{\partial
  x_{k}}$ auf $D$ vorhanden und in $x_{0}$ stetig, so ist $f$ in
  $x_{0}$ differenzierbar. Ist $f \in C^{1}\left(D,
  \mathbb{R}^{m}\right),$ so ist $f$ auf $D$ differenzierbar.\\
</div>
<div>
  \textbf{Beispiel:}\\
</div>
<div>
  $D=\mathbb{R}^{2}, f(x, y)=(\underbrace{x+y}_{f_{1}(x, y)}
  \underbrace{x y}_{f_{2}(x, y)} \underbrace{x^{2} y}_{f_{3}(x,
  y)}) .$ Es gilt $f \in C^{1}\left(\mathbb{R}^{2},
  \mathbb{R}^{3}\right)$ \[ \begin{array}{c} \frac{\partial
  f_{1}}{\partial x}(x, y)=1, \frac{\partial f_{1}}{\partial y}(x,
  y)=1, \frac{\partial f_{2}}{\partial x}(x, y)=y, \\
  \frac{\partial f_{2}}{\partial y}(x, y)=x, \frac{\partial
  f_{3}}{\partial x}(x, y)=2 x y, \frac{\partial f_{3}}{\partial
  y}(x, y)=x^{2}. \end{array} \] Also: $f^{\prime}(x, y)=J_{f}(x,
  y)=\left(\begin{array}{cc}1 & 1 \\ y & x \\ 2 x y &
  x^{2}\end{array}\right).$
</div>
