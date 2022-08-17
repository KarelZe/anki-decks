## Note
nid: 1609155711965
model: Basic-d7a3e
tags: 05_evaluation, checklater
markdown: false

### Front
<p>Was ist der Kappa-Koeffizient?</p>

### Back
<p>Der Kappa-Koeffizient vergleicht die Prognosequalität eines
Klassifizierers durch Vergleich mit einem Referenz-Klassifizierer.
<p><b>Beispiel:</b>
<p>Klassifizierer 1:
<p><img src="12ERj2z7vnAySgPRm4wZ.png" style="width: 366px;">
<p><b>Referenz-Klassifizierer:</b>
<p><img src="1NAr32GaXaFXRKnc74pL.png" style="width: 366px;">
<p><b>Kappa-Koeffizient:</b>
<p>\(\kappa=\frac{140-(60+18+4)}{200-(60+18+4)}=\frac{58}{118}=49,2
\%\)
<p>Einträge auf der Diagonalen werden herausgerechnet.
<p>Im Nenner wird die Verbesserung zur maximal möglichen
Verbesserung ins Verhältnis gesetzt. Formaler:
<p>\(\kappa=\frac{\text { Number of observed successes }-\text {
Number of expected successes }}{\text { Total number of possible
successes }-\text { Number of expected sucsesses }}\)
<p><b>Alternativ</b>:
<p>\(\text { Kappa Statistic
}=\frac{\left(P_{a}-P_{e}\right)}{\left(1-P_{e}\right)} \)
<p>wobei TP, TN, FP, und FN definiert sind als
\(P_{a}=[(\mathrm{TP}+\mathrm{TN}) / \mathrm{N}]\), and
\(P_{e}=[(\mathrm{TP}+\mathrm{FN}] /
\mathrm{N}][(\mathrm{TP}+\mathrm{FN}) / \mathrm{N}]\) .
