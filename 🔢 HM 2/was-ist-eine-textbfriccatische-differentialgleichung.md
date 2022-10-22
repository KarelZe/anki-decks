# Note
```
guid: pvRIH{D9[j
notetype: LaTeX-deb4a
```

### Tags
```
21_spezielle_differntialgelichungen_1_ordnung
```

## Front
Was ist eine \textbf{Riccatische Differentialgleichung}?

## Back
Seien $g, h, k \in C(I, \mathbb{R}) .$ Die Differentialgleichung \[
(* *) \quad y^{\prime}(x)+g(x) y(x)+h(x) y^{2}(x)=k(x) \] heißt
\textbf{Riccatische Differentialgleichung}. Sind $y_{1}, y_{2}$
Lösungen von $(* *)$ auf $I_{1} \subseteq I,$ so gilt für
$u:=y_{1}-y_{2}$: \[ \begin{aligned} u^{\prime}(x)
&=\left[-g(x)
y_{1}(x)-h(x)\left(y_{1}(x)\right)^{2}+k(x)\right]-\left[-g(x)
y_{2}(x)-h(x)\left(y_{2}(x)\right)^{2}+k(x)\right] \\ &=-g(x)
u(x)-h(x)\left(\left(y_{1}(x)\right)^{2}-\left(y_{2}(x)\right)^{2}\right)
\\ &=-g(x) u(x)-h(x) u(x)\left(y_{1}(x)+y_{2}(x)\right) \\
&=-g(x) u(x)-h(x) u(x)\left(u(x)+2 y_{2}(x)\right) \\
&=-\left(g(x)+2 h(x) y_{2}(x)\right) u(x)-h(x) u^{2}(x).
\end{aligned} \]
<div>
  \textbf{Fazit}:
</div>
<div>
  Ist eine Lösung $y_{2}$ von $(* *)$ bekannt (z.B. durch "erraten"
  ), so liefern Lösungen $u \neq 0$ obiger Bernoulli
  Differentialgleichung für $u$ weitere Lösungen von $(* *)$ der
  Form $y_{2}(x)+u(x)$.
</div>
