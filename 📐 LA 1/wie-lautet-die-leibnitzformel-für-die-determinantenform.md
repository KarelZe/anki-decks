# Note
```
guid: enD`oS)Hz{
notetype: LaTeX-deb4a
```

### Tags
```
Determinante
```

## Front
Wie lautet die Leibnitzformel für die Determinantenform?

## Back
% Beispiel 5.1.15 (Leibniz-Formel)<div>
</div><div>Die eindeutige orientierte $n$-Form Det $:=e_{1}^{*} \wedge \cdots \wedge e_{n}^{*}$ auf $\mathbb{K}^{n}$ mit der Normierung $\operatorname{Det}( e_{1} , \ldots , e _ { n } ) = 1$ ist gegeben durch die Leibniz-Formel:</div><div>$$
\operatorname{Det}\left(v^{(1)}, \ldots, v^{(n)}\right)=\sum_{o \in \operatorname{Sym}_{n}} \operatorname{sgn}(\sigma)\left(\prod_{i=1}^{n} v_{\sigma(i)}^{(i)}\right)=\sum_{\sigma \in \operatorname{Sym}_{n}} \operatorname{sgn}(\sigma)\left(\prod_{i=1}^{n} v_{i}^{(\sigma(i))}\right)
$$
wobei
$$
v^{(i)}=\left(\begin{array}{c}
{v_{1}^{(i)}} \\
{\vdots} \\
{v_{n}^{(i)}}
\end{array}\right) \in \mathbb{K}^{n}
$$</div><div>
</div><div>% Strang big formula</div><div>
</div><div>\textbf{Intution}</div><div>\begin{itemize}</div><div>\item Ist $\sigma \in S_{n},$ so ist $\sigma(i) \in\{1 \ldots, n\},$ und $a_{i \sigma(i)}$ ist der Eintrag an der Stelle $(i, \sigma(i))$ der Matrix $A$.</div><div>\item Ist $\sigma \in S_{n},$ so wird bei den Faktoren des Produkts $\prod_{i=1}^{n} a_{i \sigma(i)}$ aus jeder Zeile der Matrix $\boldsymbol{A}$ genau ein Element ausgewählt.
\item Die Summe wird über alle möglichen Permutationen $\sigma$ der Menge $I_{n}=\{1, \ldots, n\}$ gebildet. </div><div>\item Wegen $\left|S_{n}\right|=n !$ besteht die Summe det $(A)$ aus $n !$ Summanden.
</div><div>\item Bildet man die Summen über die geraden und ungeraden Permutationen getrennt, so erhält man
$$
\operatorname{det}(\boldsymbol{A})=\sum_{\sigma \in A_{n}} \prod_{i=1}^{n} a_{i \sigma(i)}-\sum_{\sigma \in S_{n} \backslash A_{n}} \prod_{i=1}^{n} a_{i \sigma(i)}
$$
\item Wenn wir die $n !$ Permutationen aus $S_{n}$ durchnummerie-
ren
$$
S_{n}=\left\{\sigma_{1}, \dots, \sigma_{n}\right\}
$$
so können wir die Summenformel für die Determinante auch wie folgt schreiben:
$$
\begin{aligned}
\operatorname{det}(\boldsymbol{A})=& \sum_{k=1}^{n !} \operatorname{sgn}\left(\sigma_{k}\right) \prod_{i=1}^{n} a_{i} \sigma_{k}(i) \\
=& \operatorname{sgn}\left(\sigma_{1}\right) \prod_{i=1}^{n} a_{i} \sigma_{1}(i)+\cdots+\operatorname{sgn}\left(\sigma_{n !}\right) \prod_{i=1}^{n} a_{i} \sigma_{n 1}(i) \\
=& \operatorname{sgn}\left(\sigma_{1}\right) a_{1 \sigma_{1}(1)} \cdots a_{n \sigma_{1}(n)}+\cdots \\
& \cdots+\operatorname{sgn}\left(\sigma_{n !}\right) a_{1 \sigma_{n} !(1)} \cdots a_{n \sigma_{n !}(n)}
\end{aligned}
$$
</div><div>
</div><div>\end{itemize}</div><div>
</div><div>
</div>
