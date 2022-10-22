# Note
```
guid: djm]U0W]|4
notetype: Basic-b122e-20a86
```

### Tags
```
12_relevante_objekte_empfehlen
```

## Front
Wie lässt sich einfach ein Web-Ranking als Eigenwert-Problem
formulieren?
<div>
  Berechnen Sie den die Eigenwerte für folgenden Graph:
</div>
<div><img src="Untitled-496962fbca60e763fa4e82259f0c7a45a826ef0d.png"></div>

## Back
<div>
  <div>
    Das Web hat \(n\) Seiten. Jede Seite wird durch eine Zahl \(k
    \in 1, \ldots, k, \ldots n\) indiziert. Die Wichtigkeit der
    Seite \(k\) ist \(x_{k}\). \(x_{j}>x_{k}\) bedeutet, dass
    Seite \(j\) wichtiger als Seite \(k\) ist.
  </div>
  <div>
    Wenn \(j\) \(n_{j}\) Links enthält und einer dieser Links zeigt
    \(k\), dann erhält \(k\) von \(j\) Stimmen mit dem Gewicht
    \(x_{j} \frac{1}{n_{j}}\). \(L_{k} \subset\{1,2, \ldots, n\}\)
    ist die Menge der Seiten mit einem Link auf die Seite \(k\).
    \(n_{j}\) ist die Anzahl der Links die Seite \(j\) verlassen.
    Links auf sich selbst zählen nicht. Die Wichtigkeit der Seite
    \(k\) ist dann
  </div>
</div>
<div>
  \[x_{k}=\sum_{j \in L_{k}} \frac{x_{j}}{n_{j}}.\]
</div>\(x_{1}=x_{3} / 1+x_{4} / 2\) \(x_{2}=x_{1} / 3\)
\(x_{3}=x_{1} / 3+x_{2} / 2+x_{4} / 2\) \(x_{4}=x_{1} / 3+x_{2} /
2\)
<div>
  \(A x=x\)
  <div>
    \(x=\left(x_{1}, x_{2}, x_{3}, x_{4}\right)^{T}\)
    <div>
      \(A=\left(\begin{array}{cccc}0 & 0 & 1 & 1 / 2 \\ 1 / 3 & 0 &
      0 & 0 \\ 1 / 3 & 1 / 2 & 0 & 1 / 2 \\ 1 / 3 & 1 / 2 & 0 &
      0\end{array}\right)\)
      <div>
        \(A x=x\) entspricht dem Eigenwertproblem \(Ax = \lambda =
        1\). Man sucht Eigenvektor \(x\) für Matrix \(A\).
        <div>
          Die Spalte \(k\) von \(A\) entspricht den Stimanteilen,
          die \(k\) von anderen Seiten erhält. Die Zeile \(k\)
          entspricht den Stimmanteilen, die \(k\) von anderen
          Seiten erhält.
        </div>
        <div>
          Der Eigenvektor entspricht \(x=\left(12, 4, 9,
          6\right)^{T}\) oder skaliert \(\left(0.387, 0.129, 0.290,
          0.194\right)^{T}\).
        </div>
      </div>
    </div>
  </div>
</div>
