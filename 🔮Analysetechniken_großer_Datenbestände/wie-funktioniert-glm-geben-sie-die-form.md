## Note
nid: 1632467697223
model: Basic-d7a3e
tags: 13_theory_guided_ds
markdown: false

### Front
Wie funktioniert GLM. Geben Sie die Formel an.

### Back
<div>
  Familie von Modellen, die unterschiedliche Beziehungen von Input-
  zur Antwortvariable erlaubt.
</div>
<div>
  Ein GLM besteht aus zwei einfachen Bausteinen. Der link function
  \(g(.)\), und der Wahrscheinlichkeitsverteilung \(P(y \mid
  \boldsymbol{x})\), welche die Antwortvariable folgt.
</div>
<div>
  Mit diesen Bausteinen bestimmt sich der Mittelwert \(\mu\) der
  Zielvariable \(y\) als Funktion Linearkombination der Inputs
  \(\boldsymbol{x}\) wiefolgt:
</div>\[ \begin{aligned} g(\mu) &=\boldsymbol{w}^{T}
\boldsymbol{x}+b, \text { oder äquivalent, } \\ \mu
&=g^{-1}\left(\boldsymbol{w}^{T} \boldsymbol{x}+b\right)
\end{aligned} \] wobei \(\boldsymbol{w}\) und \(b\) und die
Parameter des GLM aus den Daten gelernt werden.
<div>
  <b>Beispiel zur Wahl der Fehlerverteilung:</b>
</div>
<div>
  System hat sehr extreme Verhalten z. B. extreme Dürre oder
  Fluten. D. h. durch Domänenwissen weiß man, dass Fehler nicht
  normalverteilt sondern Gumbel-verteilt ist.
</div>
<div>
  <b>Beispiel zur Instanzierung des GLM:</b>
  <div>
    Beziehung zwischen Geschwindigkeit einer Flüßigkeit und ihres
    sg. hydraulischen Radius: \(V=\frac{\sqrt{5}}{n} \cdot R^{2 /
    3}\).
  </div>
</div>
<div>
  Link-Function wäre dann: \(g(V)=V^{\frac{3}{2}}\).
</div>
