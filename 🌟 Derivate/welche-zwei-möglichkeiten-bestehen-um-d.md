## Note
nid: 1642408443783
model: Basic-02d89-e0e22
tags: 05_bewertung, derivate::05_bewertung
markdown: false

### Front
Welche zwei Möglichkeiten bestehen, um Dividenden während der Optionsfrist im Black-Scholes Modell zu berücksichtigen?

### Back
1. Sichere Dividende in Höhe von \(D\) in \(t_{1}\)
<ul><li>Aktienkurs sinkt in \(t_{1}\) um \(D\)</li><li>Idee: Zerlegung des Aktienkurses vor \(t_{1}\) in zwei Komponenten: Wert der sicheren Dividende \(D\). \(e^{-r\left(t_{1}-t\right)}\) und verbliebenen, unsicheren Teil \(S(t)-D \cdot e^{-r\left(t_{1}-t\right)}\)</li><li>Für die Optionsbewertung ist nur der unsichere Teil interessant \(\rightarrow\) ersetze \(S(t)\) durch \(S(t)-D \cdot e^{-r\left(t_{1}-t\right)}\)</li></ul>2. Stetige Dividendenrendite mit Rate \(\delta\)
<ul><li>Bei Reinvestition der Dividendenzahlung in die Aktie wächst der Aktienbestand mit Rate \(\delta\)</li><li>Aus einer Aktie in \(t\) werden \(e^{\delta\left(T-t\right)}\)</li><li>Ersetze in Black/Scholes-Formel \(S(t)\) durch \(S(t) e^{-\delta(T-t)}\)</li></ul>Damit bezeichnet \(d S(t)=(\mu-\delta) S d t\).
