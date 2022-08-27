## Note
nid: 1590944098425
model: LaTeX-deb4a
tags: differentialrechnung_im_R_n, wichtig
markdown: false

### Front
Was besagt der Satz über implizit defnierte Funktionen? Welche wichtigen Folgerungen sind möglich?

### Back
% Satz 19.5 (Satz über implizit definierte Funktionen (ohne
Beweis)):
<div>
  Es sei $\left(x_{0}, y_{0}\right) \in D, f\left(x_{0},
  y_{0}\right)=0$ und $\operatorname{det} \frac{\partial
  f}{\partial y}\left(x_{0}, y_{0}\right) \neq 0.$ Dann existieren
  $\delta, \eta>0$ mit folgenden Eigenschaften:
</div>
<div>
  \begin{enumerate} \item $\cdots$, \item $\cdots$, \item $\cdots$,
  \item $\forall x \in U_{\delta}\left(x_{0}\right):
  \operatorname{det} \frac{\partial f}{\partial y}(x, g(x)) \neq
  0$, \item \[ \forall x \in U_{\delta}\left(x_{0}\right):
  g^{\prime}(x)=-\left(\frac{\partial f}{\partial y}(x,
  g(x))\right)^{-1} \cdot\left(\frac{\partial f}{\partial x}(x,
  g(x))\right). \]
</div>
<div>
  \end{enumerate} \textbf{Zusatz:} Ist $f \in C^{l}\left(D,
  \mathbb{R}^{p}\right), l \geq 2,$ so ist $g \in
  C^{l}\left(U_{\delta}\left(x_{0}\right), \mathbb{R}^{p}\right)$.
</div>
