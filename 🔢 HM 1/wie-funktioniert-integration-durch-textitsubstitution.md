# Note
```
guid: v]}2h=Fb[I
notetype: LaTeX-deb4a
```

### Tags
```
```

## Front
Wie funktioniert Integration durch \textit{Substitution}?

## Back
<div>% Satz 10.15</div><div>
</div><div>Es seien $I$ und $J$ Intervalle in $\mathbb{R},$ es sei $f \in C(I), g \in C^{1}(J)$ und $g(J) \subseteq I$.</div><div>\begin{enumerate}
\item Es gilt
$$
\int f(g(t)) g^{\prime}(t) d t=\left.\int f(x) d x\right|_{x=g(t)} \text { auf } J.
$$
\item Es sei $g^{\prime}(t) \neq 0(t \in J) \Leftrightarrow g^{\prime}>0$ auf $J$ oder $g^{\prime}<0$ auf $J \Rightarrow g$ ist streng monoton Dann gilt:
$$
\int f(x) d x=\left.\int f(g(t)) g^{\prime}(t) d t\right|_{t=g^{-1}(x)} \text { auf } I.
$$
\item Ist $I=\langle a, b\rangle, J=\langle\alpha, \beta\rangle, g(\alpha)=a$ und $g(\beta)=b,$ so gilt
$$
\int_{a}^{b} f(x) d x=\int_{\alpha}^{\beta} f(g(t)) g^{\prime}(t) d t.
$$
</div><div>\end{enumerate}</div><div>
</div><div>\textbf{Merkregel:}\\</div><div>
</div><div>Ist $y=y(x)$ eine differenzierbare Funktion, so schreibt man für $y^{\prime}$ auch $\frac{d y}{d x}$ Zu 10.15: Substituiere $x=g(t),$ fasse also $x$ als Funktion von $t$ auf. Dann: $\frac{d x}{d t}=g^{\prime}(t)$ also
$$
^{"} d x=g^{\prime}(t) d t^{"}
$$
</div><div>
</div>
