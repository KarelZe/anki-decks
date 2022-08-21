## Note
nid: 1609433131741
model: Basic-d7a3e
tags: 02_statistik, checklater, ultra
markdown: false

### Front
<p>Wie funktioniert der <b>Chi-Quadrat-Test</b>?</p>

### Back
<div>Man möchte für zwei (diskrete) Verteilungen von Zufallsvariablen \(X\) und \(Y\) prüfen, ob diese unabhängig sind.</div><div>
</div><div>Zunächst bestimmt man <b>absolute Häufigkeit</b> ermittelt, wie oft die Ausprägungen \(i= 1, \cdots, m_1\) des Merkmals \(X\) und die Ausprägungen \(j = 1, \cdots, m_2\) des Merkmals \(Y\) vorkommen, sowie wie häufig die Kombination beider <b>tatsächlich </b>auftritt (\(n_{ij}\)). </div><div>
</div><div>Unter Annahme von Unabhängigkeit ermittelt man dann den <b>erwartete absolute Häufigkeit </b>(Zeilensumme der einen Merkmalausprägung * Spaltensumme der anderen Merkmalausprägung / Gesamtanzahl):</div><div>\(e_{i j}=\frac{1}{n}\left(\sum_{k=1}^{m_{1}} n_{i k}\right) \cdot\left(\sum_{k=1}^{m_{2}} n_{k j}\right)\)
</div><div>
</div><div>Der Chi-Quadrat-Wert wird dann als Summe über alle Abweichungen zwischen beobachteter und erwarteter absoluten Häufigkeit ermittelt.</div><div>
</div><div>\(\chi^{2}\)-Wert: \(\quad \chi^{2}=\sum_{i=1}^{m_{1}} \sum_{j=1}^{m_{2}} \frac{\left(n_{i j}-e_{i j}\right)^{2}}{e_{i j}}\)
</div><div>
</div><div>\(\chi^2\) ist groß, sofern Einzelabweichungen groß sind. Aus  \(\chi^2\) wird \(p\)-Wert ermittelt. \(p\) ist die Wahrscheinlichkeit bei Unabhängigkeit. Dieser kann gegen einen Schwellwert \(\alpha\) verglichen werden.</div><div>
</div><div>Hypothese, dass Verteilungen unabhängig sind, wird zurückgewiesen, wenn Wahrscheinlichkeit \(\leq \alpha\) (irgendein Schwellenwert z. B. \(\alpha = 0.01\))</div>
