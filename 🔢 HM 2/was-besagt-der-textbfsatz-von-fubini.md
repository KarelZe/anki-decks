## Note
nid: 1591513441177
model: LaTeX-deb4a
tags: Integration_im_R_n, wichtig
markdown: false

### Front
Was besagt der \textbf{Satz von Fubini}?

### Back
% Satz 20.3 (Satz von Fubini):
<div>
  Es seien $p, q \in \mathbb{N}, n=p+q\left(\text {also }
  \mathbb{R}^{n}=\mathbb{R}^{p} \times \mathbb{R}^{q}\right)$. Es
  sei I$_{1}$ ein kompaktes Intervall im $\mathbb{R}^{p}, I_{2}$
  sei ein kompaktes Intervall im $\mathbb{R}^{q},$ es sei $I:=I_{1}
  \times I_{2} \subseteq \mathbb{R}^{n}$ und $f \in R(I) .$ Punkte
  in I bezeichnen wir mit $(x, y),$ wobei $x \in I_{1}$ und $y \in
  I_{2}$. \begin{enumerate}
</div>
<div>
  \item Für jedes feste $y \in I_{2}$ sei die Funktion $x \mapsto
  f(x, y)$ integrierbar über $I_{1}$ und es sei $g(y):=\int_{I_{1}}
  f(x, y) d x .$ Dann gilt $g \in R\left(I_{2}\right) u n d$ \[
  \int_{I} f(x, y) d(x, y)=\int_{I_{2}} g(y) d
  y=\int_{I_{2}}\left(\int_{I_{1}} f(x, y) d x\right) d y. \] \item
  Für jedes feste $x \in I_{1}$ sei die Funktion $y \mapsto f(x,
  y)$ integrierbar über $I_{2}$ und es sei $g(x):=\int_{I_{2}} f(x,
  y) d y .$ Dann gilt $g \in R\left(I_{1}\right)$ und \[ \int_{I}
  f(x, y) d(x, y)=\int_{I_{1}} g(x) d
  x=\int_{I_{1}}\left(\int_{I_{2}} f(x, y) d y\right) d x. \]
</div>
<div>
  \end{enumerate}
</div>
