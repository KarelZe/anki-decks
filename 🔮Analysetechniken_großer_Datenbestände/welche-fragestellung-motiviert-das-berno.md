## Note
nid: 1632641995073
model: Basic-d7a3e
tags: 02_statistik, checklater, ultra
markdown: false

### Front
Welche Fragestellung motiviert das Bernoulli-Experiment? Wie geht man vor?

### Back
Gegeben einer beobachteten Erfolgsquote \(f\), wie groß ist die Erfolgswahrscheinlichkeit \(p\) wahrscheinlich? Z. B. in welchem Intervall liegt \(p\) mit 95%-iger Wahrscheinlichkeit? (D. h. ist Intervall bei Münzwurf sehr breit z. B 0.4 -0.6 oder eng z. B. 0.499 - 0.511?)<div>
</div><div>Oder:</div><div>
</div><div>\(\operatorname{Pr}[-z \leq X \leq z]=c\), wobei \(c\) das Konfidenzniveau ist,</div><div>wobei \(X\) die Zufallsvariable ist (hier \(p\)). 
</div><div>
</div><div>Für Standard-Normalverteilung ist es wegen Symmetrie ausreichend, nur oberen Teil zu betrachten:</div><div>\(\operatorname{Pr}[X \geq z]\).
</div><div>
</div><div>Aus Tabelle lässt sich dann \(z\)-Wert ablesen. Man gibt hierfür nur \(c\) vor. <b>\(z\) ist das Vielfache der Standardabweichung. </b>Z. B. ist \(\operatorname{Pr}[X \geq z] = 0.1\) für \(z\)-Wert 3.09.</div><div>
</div><div>Dann muss \(f\) (beobachtete Erfolgsquote) überführt werden in Zufallsvariable mit Mittelwert 0 und Standardabweichung 1, da Mittelwert und Standardabweichung davon verschieden sind. Im Ausdruck unten wird Mittelwert \(p\) abgezogen und mit Standardabweichung im Zähler bereinigt. \(N\) ist die Zahl der Experimente.</div><div>
</div><div>Transformation mit:</div><div>\(\operatorname{Pr}\left[-z<\frac{f-p}{\sqrt{p \cdot(1-p) / N}}<z\right]=c\)
</div><div>
</div><div>Man ermittelt dann für \(c\) (Konfidenz) den \(z\)-Wert anhand einer Tabelle und löst die Gleichung nach \(p\) auf, wodurch man das Intervall erhält.</div><div>
</div>
