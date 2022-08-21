## Note
nid: 1588099070225
model: Basic-b122e
tags: 02_assoziationsregeln
markdown: false

### Front
Nennen Sie Vor- und Nachteile von Assoziationsregeln

### Back
<div><div><strong>Vorteile</strong></div>
<ul>
<li>Assoziationsregeln
 machen keine Modellannahmen z. B. über Unabhängigkeit von 
Kaufprozessen. D.h. insbesondere keine statistischen Annahmen.</li><li>Finden interessanter Warenkörbe mit mehr als 2 Artikeln möglich.</li>
<li>Beschränkung der Berechnungen je nach Anzahl gewünschter Empfehlungen möglich, weil sich Berechnung iterativ fortsetzt.</li>
<li>Keine Wahl von Cut-Methoden nötig.</li>
</ul>
<div><strong>Nachteile</strong></div>
<ul>
<li>Erfodert zwei, nicht aus dem Modell begründbare Parameter (Mindestsupport, Mindestkonfidenz)</li>
<li>Ex ante 
lassen sich Parameter kaum bestimmen. Sondern nur in einem iterativen 
Prozess. Häufig unterschiedliche Parameter für verschiedene Warengruppen</li>
<li>Verfahren berücksichtigt keine statistischen Zusammenhänge</li>
</ul>
</div>
