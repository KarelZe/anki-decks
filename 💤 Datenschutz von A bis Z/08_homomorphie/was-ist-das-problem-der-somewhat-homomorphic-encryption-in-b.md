# Note
```
guid: t-Xp]V5Sw.
notetype: Basic-9c783
```

### Tags
```
datenschutz::08-homomorphe-verschluesselung
```

## Front
Was ist das <b>Problem </b>der <b>Somewhat Homomorphic Encryption</b> in Bezug auf <b>Noise</b>? Wie wird es <b>gelöst</b>?

## Back
Noise ist Fluch und Segen. Einerseits macht das Rauschen Systeme sicher, anderseits nimmt mit Addition und Multiplikation der Noise zu.

Entschlüsselung schlägt dann fehl, wenn mehr Noise-Bits als Bits in Hilfswert \(q\) sind. Sprich der zugrundeliegende Wert wäre verloren.

Einfache Lösung besteht darin, das Rauschen zu verringern. Häufig gelöst durch <b>Bootstrapping</b>.

<b>Visualisierung:</b>
<img src="paste-2e7cb4c4ec99c11df246f744ede02301ff42c8bc.jpg">
<img src="paste-e9de4720d2617768a2e5a7b3b76fc166256309c2.jpg">
