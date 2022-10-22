# Note
```
guid: Bd]5e<IXHH
notetype: Basic-9c783
```

### Tags
```
datenschutz::03_masse
ultra
```

## Front
Was ist <b>Entropy-</b>\(\ell\)<b>-Diversity</b>?

## Back
Basiert auf der vorgestellten Idee der Bayes-Optimal Policy.
Gegeben eine Tabelle \(\mathbf{T}\) und die generalisierte Tabelle
\(\mathbf{T}^*\), ein Attribut \(\mathbf{q}^*\) als generalisierter
Wert von \(\mathbf{q}\), ein \(\mathbf{q}^*\)-Block ist eine Menge
von Tupeln aus \(\mathrm{T}^*\), deren nicht-sensiblen Attribute zu
\(\mathbf{q}^*\) generalisiert wurden. <b>Definition Entropie
I-Diversity:</b> Eine Tabelle ist Entropy-l-Diverse, wenn für jeden
\(q^*\)-Block gilt: \[-\sum_{s \in S} P_{(q *, s)} \log \left(P_{(q
*, s)}\right) \geq \log (l) \text { und } P_{\left(q^*,
s\right)}=\frac{n_{\left(q^*, s\right)}}{\sum_{s^{\prime} \in S}
n_{\left(q^*, s^{\prime}\right)}}\](10er Logarithmus)
\(P_{\left(q^*, s\right)}\) ist der Anteil der Datensätze in
\(q^*\), der den Wert s hat I ist minimales Maß der Unordnung in
den Blöcken <b>Beispiel:</b> (Im zweiten Beispiel soll Entropie
größer sein als log(Angabe)) <img src="paste-247d7554ebe64f15c2b343ffdfffc8518d660ceb.jpg">
