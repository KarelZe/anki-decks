## Note
nid: 1604950436611
model: Basic-d7a3e
tags: 03_vorlesung, 04_uebung, 04_uebung_rs, 09_para_prozess_block, checklater, klausur
markdown: false

### Front
<p>Was ist das Gesetz von Amdahl? Leiten Sie es her.

### Back
<p>Abschätzung des erzielbaren Speed-Ups nach oben (obere
Schranke).
<p><b>Gesamtausführungszeit</b> \(T(n)\)
<p>\(\mathrm{T}(\mathrm{n})=\mathrm{T}(1) \times
\frac{1-\mathrm{a}}{\mathrm{n}}+\mathrm{T}(1) \times \mathrm{a}\),
<p>wobei \(a\) den <i>sequentiellen Programmanteil</i> angibt.
<p>
<b>Beschleunigung</b>\(\mathrm{S}(\mathrm{n})=\frac{\mathrm{T}(1)}{\mathrm{T}(\mathrm{n})}=\frac{\mathrm{T}(1)}{\mathrm{T}(1)
\times \frac{1-\mathrm{a}}{\mathrm{n}}+\mathrm{T}(1) \times
\mathrm{a}}=\frac{1}{\frac{1-\mathrm{a}}{\mathrm{n}}+\mathrm{a}}\)
<p>Für \(n \rightarrow \infty:
\mathrm{S}(\mathrm{n})=\frac{1}{\mathrm{a}}\)
