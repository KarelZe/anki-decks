## Note
nid: 1637153818312
model: Basic-d7a3e-4ce08
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Welche Entwurfsfragen sind bei Pipelines zu beachten?

### Back
<img src="paste-f40eeeee8b93d7930237eec575a2847a67ecd391.jpg">
<div>
  <b>push</b>: Erster der Daten produziert, triggert
  Folgekomponenten.
</div>
<div>
  <b>pull</b>: Letztes Element, das Daten haben will, triggert
  Vorgänger.
</div>
<div>
  <b>parallel</b>: Mehr als eine Komponente kann aktiv sein. Ggf.
  auf Anwedungsebene schwierig.
</div>
<div>
  <b>filtering</b>:
</div>
<div>
  <b>buffering</b>: Produziert eine Komponente mehr Daten als
  Folgekomponente verarbeiten kann, wird gepuffert.
</div>
