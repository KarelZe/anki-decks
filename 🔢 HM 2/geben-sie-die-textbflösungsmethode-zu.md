## Note
nid: 1593853937410
model: LaTeX-deb4a
tags: 22_lineare_systeme_mit_konstanten_koeffizienten, wichtig
markdown: false

### Front
Geben Sie die \textbf{Lösungsmethode} zur Lösung \textbf{Linearer Systeme mit konstanten Koeeffizienten} an.

### Back
% abgeleitet aus satz 22.1
<div>
  \begin{enumerate}
</div>
<div>
  \item Bestimme die verschiedenen Eigenwerte $\lambda_{1}, \ldots
  \lambda_{r}$ von $A(r \leq n)$ und deren (algebraische $)$
  Vielfachheit $k_{1}, \ldots, k_{r},$ also \[
  p(\lambda)=(-1)^{n}\left(\lambda-\lambda_{1}\right)^{k_{1}} \cdot
  \ldots \cdot\left(\lambda-\lambda_{r}\right)^{k_{r}}. \] Ordne
  diese wie folgt an: \[ \lambda_{1}, \ldots, \lambda_{m} \in
  \mathbb{R}, \lambda_{m+1}, \ldots, \lambda_{r} \in \mathbb{C}
  \backslash \mathbb{R} \] $\operatorname{mit}
  \lambda_{m+1}=\mu_{1}, \ldots, \lambda_{m+s}=\mu_{s}$ und
  $\lambda_{m+s+1}=\overline{\mu_{1}}, \ldots,
  \lambda_{r}=\overline{\mu_{s}} .$ Setze \[ M:=\left\{\lambda_{1},
  \ldots, \lambda_{m}, \lambda_{m+1}, \ldots,
  \lambda_{m+s}\right\}; \] $\lambda_{m+s+1}, \ldots, \lambda_{r}$
  bleiben unberücksichtigt! \item Für jedes $\lambda_{j} \in M$
  bestimme man eine Basis von
  $V_{j}:=\operatorname{kern}\left(A-\lambda_{j} I\right)^{k_{j}}$
  wie folgt: Bestimme eine Basis von kern $\left(A-\lambda_{j}
  I\right),$ ergänze diese zu einer Basis von \[
  \operatorname{kern}\left(A-\lambda_{j} I\right)^{2}, \ldots \]
  \item Es sei $\lambda_{j} \in M$ und $v$ ein Basisvektor von
  $V_{j}$. Setze $y(x):=$ \[ e^{\lambda_{j} x}\left(v+\frac{x}{1
  !}\left(A-\lambda_{j} I\right) v+\frac{x^{2}}{2
  !}\left(A-\lambda_{j} I\right)^{2} v+. .
  .+\frac{x^{k_{j}-1}}{\left(k_{j}-1\right) !}\left(A-\lambda_{j}
  I\right)^{k_{j}-1} v\right). \] Fall 1: $\lambda_{j} \in
  \mathbb{R} .$ Dann ist $y(x) \in \mathbb{R}^{n}(x \in
  \mathbb{R})$ und $y$ ist eine Lösung von (2) auf $\mathbb{R}$.
</div>
<div>
  Fall 2: $\lambda_{j} \in \mathbb{C} \backslash \mathbb{R} .$ Dann
  ist $y(x) \in \mathbb{C}^{n}(x \in \mathbb{R}) .$ Zerlege $y(x)$
  komponentenweise in Real- und Imaginärteil: \[
  y(x)=\underbrace{y^{(1)}(x)}_{\in \mathbb{R}^{n}}+i
  \underbrace{y^{(2)}(x)}_{\in \mathbb{R}^{n}} \] Dann sind
  $y^{(1)}, y^{(2)}$ linear unabhängige Lösungen von (2) auf
  $\mathbb{R}$.
</div>
<div>
  \item Führt man 3. für jedes $\lambda_{j} \in M$ und jeden
  Basisvektor von $V_{j}$ durch, so erhält man ein
  Fundamentalsystem von (2).
</div>
<div>
  \end{enumerate}
</div>
