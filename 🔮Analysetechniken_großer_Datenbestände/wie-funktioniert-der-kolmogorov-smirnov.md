## Note
nid: 1609435249352
model: Basic-d7a3e
tags: 02_statistik, checklater, ultra
markdown: false

### Front
<p>Wie funktioniert der <b>Kolmogorov-Smirnov-Test</b>?</p>

### Back
<p><b>Konzeption</b>:
<div>
  Test, ob zwei Verteilungsfunktionen übereinstimmen.
</div>
<div>
  Nullhypothese: \(H_0: F_X(x) = F_0(x)\) (soll verworfen werden)
</div>
<div>
  Vergleich der empirischen Verteilungsfunktion \(F_X\) mit
  hypothetischer Verteilungsfunktion \(F_0\).
</div>
<div>
  <b>Erklärung</b>:
</div>
<div>
  Zunächst werden die empirischen Beobachtungswerte \(x_i\)
  aufsteigend sortiert.
</div>
<div>
  Dann wird die relative Summe gebildet (\(S(x_i)\)) (empirische
  Verteilungsfunktion).
</div>
<div>
  Dann erfolgt ein Vergleich der empirischen Verteilung mit einer
  hypothetischen Verteilung \(F_0(x_i)\). Folgt \(X\) der
  Verteilung, so müsste die Differenz gering sein.
</div>
<div>
  Die Differenz wird wiefolgt ermittelt:
</div>
<div>
  \(d_{\max }=\max \left(\max _{i=1, \ldots,
  n}\left|S\left(x_{i}\right)-F_{0}\left(x_{i}\right)\right|, \max
  _{i=1, \ldots,
  n}\left|S\left(x_{i-1}\right)-F_{0}\left(x_{i}\right)\right|\right)\)
</div>
<div>
  Dies ist notwendig, da einmal vor und einmal nach Summenbildung
  betrachtet wird.
</div>
<div>
  Übersteigt \(d_{\max}\) \(d_{\alpha}\), dann wird Hypothese
  abgelehnt für Signifikanzniveau \(\alpha\).
</div>
<div><img src="1024px-KS-Test.png"></div>
<div>
  <b>Intuition</b>:
</div>
<div>
  Die <b>maximale Distanz</b> zwischen kummulativen
  Häufigkeitsverteilungen ist Grundlage für Entscheidung.
</div>
