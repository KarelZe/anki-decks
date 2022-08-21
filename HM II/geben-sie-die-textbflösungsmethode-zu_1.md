## Note
nid: 1594490747209
model: LaTeX
tags: lineare_differentialgleichung_nte_ordnung, wichtig
markdown: false

### Front
Geben Sie die \textbf{Lösungsmethode} zur Lösung von \textbf{linearen Differentialgleichungen $n$-ter Ordnung mit konstanten Koeffizienten} für \textbf{homogene Gleichungen} an.

### Back
\textbf{Erinnerung}
<div>
  Die Differentialgleichung \begin{equation} (L y)(x)=b(x)
  \end{equation} heißt lineare Differentialgleichung $n$ -ter
  Ordnung mit konstanten Koeffizienten. Die Gleichung
  \begin{equation} (L y)(x)=0 \end{equation} heißt die zu (1)
  gehörige homogene Gleichung ((1) heißt inhomogen, falls $b \neq
  0$ ).\\
</div>
<div>
  \textbf{Lösungsmethode}
</div>
<div>
  \[ \text { Lösungsmethode für }(2): y^{(n)}(x)+a_{n-1}
  y^{(n-1)}(x)+\ldots+a_{1} y^{\prime}(x)+a_{0} y(x)=0 \] Das
  Polynom \[ p(\lambda):=\lambda^{n}+a_{n-1} \lambda^{n-1}+\ldots
  a_{1} \lambda+a_{0} \] heißt charakteristisches Polynom für (2).
  Wie in $\$ 22$ sei \[
  p(\lambda)=\left(\lambda-\lambda_{1}\right)^{k_{1}}\left(\lambda-\lambda_{2}\right)^{k_{2}}
  \cdot \ldots
  \cdot\left(\lambda-\lambda_{r}\right)^{k_{r}}\left(\lambda_{i}
  \neq \lambda_{j} \text { für } i \neq j\right). \]
</div>
<div>
  \begin{enumerate} \item Mit \[ \lambda_{1}, \ldots, \lambda_{m}
  \in \mathbb{R}, \lambda_{m+1}=\mu_{1}, \ldots,
  \lambda_{m+s}=\mu_{s} \in \mathbb{C} \backslash \mathbb{R},
  \lambda_{m+s+1}=\overline{\mu_{1}}, \ldots,
  \lambda_{r}=\overline{\mu_{s}} \] sei \[ M:=\left\{\lambda_{1},
  \ldots, \lambda_{m}, \lambda_{m+1}, \ldots, \lambda_{m+s}\right\}
  \] \item Es sei $\lambda_{j} \in M$ Fall $1: \lambda_{j} \in
  \mathbb{R} .$ Dann sind \[ e^{\lambda_{j} x}, x e^{\lambda_{j}
  x}, \ldots, x^{k_{j}-1} e^{\lambda_{j} x}. \] $k_{j}$ linear
  unabhängige Lösungen von (2). Fall $2: \lambda_{j}=\alpha+i \beta
  \in \mathbb{C} \backslash \mathbb{R},$ also $\alpha, \beta \in
  \mathbb{R}, \beta \neq 0 .$ Dann sind \[ \begin{array}{l}
  e^{\alpha x} \cos \beta x, x e^{\alpha x} \cos \beta x, \ldots,
  x^{k j-1} e^{\alpha x} \cos \beta x \\ e^{\alpha x} \sin \beta x,
  x e^{\alpha x} \sin \beta x, \ldots, x^{k_{j}-1} e^{\alpha x}
  \sin \beta x \end{array} \] $2 k_{j}$ linear unabhängige Lösungen
  von (2).
</div>
<div>
  \item Führt man 2. für jedes $\lambda_{j} \in M$ durch, so erhält
  man ein Fundamentalsystem von (2).
</div>
<div>
  \end{enumerate}
</div>
