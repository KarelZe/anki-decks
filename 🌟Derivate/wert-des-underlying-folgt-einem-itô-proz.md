## Note
nid: 1642523180062
model: Basic-02d89
tags: 05_bewertung, checklater
markdown: false

### Front
Wert des Underlying folgt einem Itô Prozess \(d x=\alpha(x, t) d t+\sigma(x, t) d w\) Preis \(f\) eines Derivats hängt von Wert des Underlying \(x\) und der Zeit \(t\) ab.

Man sucht \(d f(x, t)\). Wie lautet Ito's Lemma?

### Back
\(\begin{aligned} d f &=f_{t} \cdot d t+f_{x} \cdot d x+\frac{1}{2} f_{x x}(d x)^{2} \\ &=f_{t} \cdot d t+f_{x} \cdot d x+\frac{1}{2} f_{x x} \cdot \sigma(x, t)^{2} d t \\ &=\left(f_{t}+f_{x} \cdot \alpha(x, t)+\frac{1}{2} f_{x x} \cdot \sigma(x, t)^{2}\right) d t+f_{x} \cdot \sigma(x, t) d w \end{aligned}\)
