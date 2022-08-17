## Note
nid: 1635056292285
model: Basic-d7a3e
tags: 07_case_studies
markdown: false

### Front
Erklären Sie den <b>Use Case</b> bei IBM von <b>Palladio</b>.

### Back
<div>
  <b>Problem</b>:
</div>
<div>
  Verschiedene Design-Alternativen für die
  Speicher-Virtualisierungen (8-schichtig) auf dem SystemZ sollen
  untersucht werden. Man wollte wissen, ob man asynchrone neben
  synchronen Zugriffe erlauben soll. Die Performanz soll optimiert
  werden, indem Flaschenhälse aufgedeckt werden.
</div>
<div>
  <b>Vorgehen</b>:
</div>
<div><img src=
"paste-5b1698a19bce2ccff61866b0d305ae99fa3170d8.jpg"></div>
<div>
  Man hat synchrones und asynchrones Modell verglichen. Als Input
  dienten Architekturdaten.
</div>
<div>
  <b>Ergebnisse</b>:
</div>
<div>
  Keine Vorteile durch asynchronen Aufruf, weil bei synchronen
  Aufrufen Hardware gut ausgenutzt werden. Anzahl der synchronen
  Aufrufe wird clientseitig begrenzt. Mit asynchronem Aufruf wurde
  Bottleneck auf Server verschoben.
</div>
<div>
  Hoher Modellierungsaufwand, aber deutlich günstiger als eine
  Performanz-Prototyp. Gut geeignet für What-if Analysen und um
  Bottlenecks zu finden. Hilft das System besser zu verstehen.
</div>
