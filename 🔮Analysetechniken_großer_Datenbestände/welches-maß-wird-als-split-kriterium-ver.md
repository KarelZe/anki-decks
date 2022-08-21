## Note
nid: 1606220333600
model: Basic-d7a3e
tags: 04_entscheidungsbaeume, checklater
markdown: false

### Front
<p>Welches Maß wird als <b>Split-Kriterium</b> verwendet?</p><p>Wie ist das Maß definiert und wie funktioniert es?</p>

### Back
<b>Entropie:</b>
<div>
  \[E(S)=-\sum_{j} p_{j} \cdot \log p_{j},\]
  <p>wobei \(p_j\) die relative Häufigkeit von Klasse \(j\) in
  \(S\) ist.
  <p><b>Entropie eines Splits:</b>
  <p>\[E\left(S_{1}, S_{2}\right)=\frac{n_{1}}{n}
  E\left(S_{1}\right)+\frac{n_{2}}{n} E\left(S_{2}\right).\]
  <p>\(S\) ist dabei der Datenbestand und \(n\) die Zahl der
  Datenobjekte. \(S_1\) und \(S_2\) die Teilmengen, die im linken
  oder rechten Teilbaum landen.
</div>
