## Note
nid: 1592742163513
model: Basic-d7a3e-4ce08
tags: 05_modelling_quality, performance
markdown: false

### Front
Was sind jeweils Vor- und Nachteile von <b>Analytic</b> vs.
<b>Design Models</b>?

### Back
<p><strong>Analyse-orienterte Modelle</strong>
<p><em>Pros</em>
<ul>
  <li>Weniger teuer in der Konstruktion und Ausführung z. B. weil
  gestaltet mit Warteschlagenmodell o. Ä.
  <li>Reicht um z. B. zu variieren äußere Faktoren zu variieren z.
  B. mehr Last / weniger Last.
</ul>
<p><em>Cons</em>
<ul>
  <li>Begrenzte Aussagekraft und Genauigkeit z<em>. B. lässt sich
  analytisch nur schwer beantworten, wo Cache eingebaut werden
  soll.</em>
</ul>
<p><strong>Design-orienterte Modelle</strong>
<p><em>Pros</em>
<ul>
  <li>Bessere Aussagekraft. Kann so detailliert ausgestaltet werden
  wie es benötigt wird. <i>z. B. Man kann ausdrücken, wo Cache
  eingebaut werden soll.</i> Immer, wenn was an interner Struktur
  geändert werden soll.
</ul>
<p><em>Cons</em>
<ul>
  <li>Teuer in der Entwicklung, Validierung und Ausführung. <i>z.
  B. mehr Annahmen, mehr modellieren</i>
</ul>
