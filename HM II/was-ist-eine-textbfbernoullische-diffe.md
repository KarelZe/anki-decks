## Note
nid: 1593247052513
model: LaTeX
tags: 21_spezielle_differntialgelichungen_1_ordnung
markdown: false

### Front
Was ist eine \textbf{Bernoullische Differentialgleichung}?

### Back
Es sei $I \subseteq \mathbb{R}$ ein Intervall, $g, h \in C(I,
\mathbb{R})$ und $\alpha \in \mathbb{R} .$ Die
Differentialgleichung $$
<div>
  (*) \quad y^{\prime}(x)+g(x) y(x)+h(x)(y(x))^{\alpha}=0
</div>
<div>
  $$ heißt \textbf{Bernoullische Differentialgleichung}. Im Fall
  $\alpha=0$ erhält man eine lineare Differentialgleichung
  (inhomogen, falls $h \neq 0$ ). Im Fall $\alpha=1$ erhält man
  eine homogene lineare Differentialgleichung.\\
  <div>
    Nun sei $\alpha \in \mathbb{R} \backslash\{0,1\} .$ Wir
    betrachten die Transformation $z(x)=(y(x))^{1-\alpha}$: \[
    \begin{aligned} z^{\prime}(x) &=(1-\alpha)(y(x))^{-\alpha}
    y^{\prime}(x) \\ &=(1-\alpha)(y(x))^{-\alpha}\left(-g(x)
    y(x)-h(x)(y(x))^{\alpha}\right) \\ &=-(1-\alpha)
    g(x)(y(x))^{1-\alpha}-(1-\alpha) h(x) \\ &=-(1-\alpha) g(x)
    z(x)-(1-\alpha) h(x). \end{aligned} \]
  </div>
</div>
