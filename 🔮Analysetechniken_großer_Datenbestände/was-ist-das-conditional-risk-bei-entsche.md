## Note
nid: 1606220337379
model: Basic-d7a3e
tags: 04_entscheidungsbaeume, checklater
markdown: false

### Front
<p>Was ist das <b>Conditional Risk</b> bei Entscheidungsbäumen? Wie
ist es definiert? Erklären Sie alle Komponenten.

### Back
<p>Conditional Risk erlaubt Kosten zu berücksichtigen. </p><p>\[\quad R(i \mid x)=\sum_j P(j \mid x) \cdot \operatorname{Cost}(i, j)\]
</p><p>wobei \(j\) die Laufvariable für die tatsächliche Klasse, \(i\) die vorhergesagte Klasse (d. h. Klasse, auf die wir uns einstellen) die Klasse ist, für die man in Erwägung zieht, Kunde zu betrachten z. B. schlechter Kunde. \(P(j \mid x)\) ist Wahrscheinlichkeit für neuen Kunden \(x\) in Abhängigkeit von \(j\). Man summiert über alle Klassenlabels \(j\) auf.</p><p>\(\operatorname{Cost}(i, j)\) sind Kosten für Kunde aus Klasse \(j\) und \(i\). Sie stehen dafür, ob ich Kunde als guten oder schlechten Kunde behandeln. D. h. \(i\) ist wie ich Kunde wahrnehme.</p><p><b>Beispiel:</b></p><p>Erwarteter Gewinn \(R(\text{gut} \mid x) = P(\text{gut} \mid x) * \operatorname{Cost}(\text{gut vorhergesagt}, \text{tatsächlich gut}) + P(\text{schlecht} \mid x) * \operatorname{Cost}(\text{gut vorhergesagt}, \text{tatsächlich schlecht})\)
</p><p></p>
