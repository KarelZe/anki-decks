## Note
nid: 1632461662910
model: Basic-d7a3e
tags: 05_evaluation, checklater
markdown: false

### Front
Erklären Sie das <b>F-Measure</b>. Warum ist es wichtig?

### Back
<div>
  Präzision und Recall haben jeweils ihre Schwächen z. B. bei
  unbalancierten Daten. Um sie umfassend zu betrachten, ist unser
  häufig verwendeter Indikator F-Measure.
</div>
<div>
  Je höher der F-Wert, desto effektiver ist das Modell.
</div>
<div>
  F-Measure ist das gewichtete harmonische Mittel von Precision and
  Recall.
</div>
<div>
  \[\text { F-measure }=\frac{\left(2 \times \text { Recall }
  \times \text { Precision }\right)}{(\text { Recall }+\text {
  Precision
  })}=\frac{\text{tp}}{\text{tp}+\frac{1}{2}(\text{fp}+\text{fn})}\]
</div>
<div>
  Beachte:
</div>
<div>
  Harmonisches Mittel für die Zahlen \(x_1, \cdots, x_n\) ist
  definiert als:
</div>
<div>
  \(\bar{x}_{\text {harm
  }}=\frac{n}{\frac{1}{x_{1}}+\cdots+\frac{1}{x_{n}}}\)
</div>
<div>
  Verwendet um Mittelwert von zwei Quotienten zu berechnen.
</div>
