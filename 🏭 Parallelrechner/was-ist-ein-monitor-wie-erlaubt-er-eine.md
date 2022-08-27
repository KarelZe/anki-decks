## Note
nid: 1592487099504
model: Basic-b122e-20a86
tags: 3_5_synchronisation
markdown: false

### Front
Was ist ein Monitor? Wie erlaubt er eine Synchronisation?

### Back
Ein Monitor ist eine abstrakte Datenstruktur mit impliziten
Synchronisationseigenschaften.
<div>
  Den Benutzern eines Monitors bleibt nicht nur die Implementierung
  der Zugriffsfunktionen auf gemeinsame Daten, sondern auch die
  <b>Realisierung des gegenseitigen Ausschlusses</b> für diese
  Funktion <b>verborgen</b>.
</div>
<div>
  Alle <b>Zugriffsoperationen</b> eines Monitors werden <b>im
  gegenseitigen Ausschluss</b> durchgeführt.
</div>
<div>
  Die im <b>Monitor vereinbarten Variablen</b> können aufgrund
  dieses gegenseitigen Ausschlusses <b>nie gleichzeitig</b> benutzt
  werden - sie stellen exklusive Betriebsmittel für Prozesse dar.
</div>
<div>
  Ein Prozess kann einen Monitor nur druch Aufruf einer
  Monitorprozedur betreten.
</div>
<div>
  Dabei geschieht der Eintritt in einen Monitor unter Ausschluss
  aller anderen Prozesse.
</div>
<div>
  Falls ein weiterer Prozess den Monitor betreten will, wird er
  supsendiert und wartet außen auf die Freigabe des Monitors.
</div>
