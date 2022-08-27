## Note
nid: 1642406052317
model: Basic-02d89-e0e22
tags: 05_bewertung, derivate::05_bewertung
markdown: false

### Front
Wie lässt sich Black-Scholes für <b>mehrere Wertpapiere</b> verallgemeinern?

### Back
Verallgemeinerung des Lemma 's von Itô:
Gegeben Preisvektor \(X=\left(x_{1}, x_{2}, \ldots, x_{n}\right)\) mit
\[
d x_{i}=\alpha_{i}(X, t) d t+\sigma_{i}(X, t) d w_{i}
\]
wobei Wiener Prozesse korreliert sind mit \(\rho_{i j}\) (momentane Korrelation zwischen \(w_{i}\) und \(w_{j}\) ) \(f\) sei Funktion von \(X\) und \(t\).

Verallgemeinerung des Lemma 's von Itô liefert:
\[
d f(X, t)=\left(f_{t}+\sum_{i=1}^{n} f_{x_{i}} \alpha_{i}+\frac{1}{2} \sum_{i=1}^{n} \sum_{j=1}^{n} f_{x_{i} x_{j}} \sigma_{i} \sigma_{j} \rho_{i j}\right) d t+\sum_{i=1}^{n} f_{x_{i}} \sigma_{i} d w_{i}
\]

(Die Summenterme sind jeweils die Ableitungen nach jedem WP bzw. alle WP)

Portfolio erzeugen:
\[f_{t}+\sum_{i=1}^{n} f_{x_{i}} x_{i} \cdot r+\frac{1}{2} \sum_{i=1}^{n} \sum_{j=1}^{n} f_{x_{i} x_{j}} \sigma_{i} \sigma_{j} \rho_{i j}=r \cdot f\]
