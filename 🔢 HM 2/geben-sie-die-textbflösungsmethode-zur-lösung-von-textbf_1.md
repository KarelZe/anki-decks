# Note
```
guid: G`@aHJx9/a
notetype: LaTeX-deb4a
```

### Tags
```
lineare_differentialgleichung_nte_ordnung
wichtig
```

## Front
Geben Sie die \textbf{Lösungsmethode} zur Lösung von \textbf{linearen Differentialgleichungen $n$-ter Ordnung mit konstanten Koeffizienten} für \textbf{inhomogene Gleichungen} an.

## Back
Wir betrachten nun die inhomogenen Gleichung \begin{equation} (L
y)(x)=b(x) \end{equation} für spezielle Funktionen $b: \mathbb{R}
\rightarrow \mathbb{R}$. Es seien $\gamma, \delta \in \mathbb{R}, m
\in \mathbb{N}_{0}, q$ ein Polynom vom Grad $m,$ und $b$ habe die
Gestalt \[ b(x)=q(x) e^{\gamma x} \cos (\delta x) \text { oder }
b(x)=q(x) e^{\gamma x} \sin (\delta x) \] Sei $p$ das
charakteristische Polynom von \begin{equation} (L y)(x)=0
\end{equation}
<div>
  Fall $1: p(\gamma+i \delta) \neq 0 .$ Wähle den Ansatz: \[
  y_{p}(x):=(\hat{q}(x) \cos (\delta x)+\tilde{q}(x) \sin (\delta
  x)) e^{\gamma x} \] Fall $2: \gamma+i \delta$ ist eine $\nu$
  -fache Nullstelle von $p .$ Wähle den Ansatz: \[
  y_{p}(x):=x^{\nu}(\hat{q}(x) \cos (\delta x)+\tilde{q}(x) \sin
  (\delta x)) e^{\gamma x} \] In beiden Fällen sind $\hat{q}$ und
  $\tilde{q}$ Polynome vom Grade $m .$ In beiden Fällen führt
  obiger Ansatz zu einer speziellen Lösung $y_{p}$ von (1).\\
</div>
<div>
  \textbf{Beispiel}
</div>
<div>
  Betrachte $(*)$ \[ y^{\prime \prime \prime}(x)-y^{\prime}(x)=x-1
  \]
</div>
<div>
  \begin{enumerate} \item Allgemeine Lösung von $y^{\prime \prime
  \prime}(x)-y^{\prime}(x)=0$ \[
  p(\lambda)=\lambda^{3}-\lambda=\lambda\left(\lambda^{2}-1\right)=\lambda(\lambda-1)(\lambda+1).
  \] Fundamentalsystem: $1, e^{x}, e^{-x}$ \item $b(x)=x-1 .$ Also:
  $\gamma=\delta=0, q(x)=x-1, m=1 .$ Es gilt: $p(\gamma+i
  \delta)=p(0)=0$ $\nu=1 .$ Ansatz: \[ y_{p}(x)=x(a x+b)=a x^{2}+b
  x. \] Es gilt $y_{p}^{\prime}(x)=2 a x+b ; y_{p}^{\prime \prime
  \prime}(x)=0 .$ Also: \[ x-1 \stackrel{!}{=} y_{p}^{\prime \prime
  \prime}(x)-y_{p}^{\prime}(x)=-2 a x-b \Longleftrightarrow-2 a=1,
  b=1 \] und somit $y_{p}(x)=-\frac{1}{2} x^{2}+x$. \item
  Allgemeine Lösung von $(*)$ \[ y(x)=c_{1}+c_{2} e^{x}+c_{3}
  e^{-x}-\frac{1}{2} x^{2}+x, \quad c_{1}, c_{2}, c_{3} \in
  \mathbb{R}. \]
</div>
<div>
  \end{enumerate}
</div>
