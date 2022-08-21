## Note
nid: 1591862486345
model: LaTeX
tags: Integration_im_R_n, wichtig
markdown: false

### Front
Wie ist ein \textbf{Normalbereich bzgl. der $x$-Achse} definiert?

### Back
Es seien $a, b \in \mathbb{R}, a<b, f, g \in C([a, b])$ und $f \leq g$ auf $[a, b] .$ Dann heißt die Menge
\[
B:=\left\{(x, y) \in \mathbb{R}^{2}: x \in[a, b], f(x) \leq y \leq g(x)\right\}
\]
ein \textbf{Normalbereich bzgl. der $x$ -Achse}. Nach 20.5 c) ist $B$ messbar.<div>
</div><div>Nun sei $B$ wie in obiger Definition und $h \in C(B, \mathbb{R})$. Wir berechnen $\int_{B} h(x, y) d(x, y) .$ Es
sei
\[
m:=\min f([a, b]), M:=\max g([a, b]), I:=[a, b] \times[m, M].
\]
Dann gilt:
\[
\begin{aligned}
\int_{B} h(x, y) d(x, y) &=\int_{I} h_{B}(x, y) d(x, y) \\
& \stackrel{\text {Fubini}}{=} \int_{a}^{b}\left(\int_{m}^{M} h_{B}(x, y) d y\right) d x \\
&=\int_{\mu}^{b}\left(\int_{f(x)}^{g(x)} h(x, y) d y\right) d x.
\end{aligned}
\]
</div>
