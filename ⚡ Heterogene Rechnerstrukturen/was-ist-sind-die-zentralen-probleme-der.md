## Note
nid: 1613742393956
model: Basic-d7a3e-4ce08
tags: 12_Vektorverarbeitung, het_rs::07_vektorprozessoren
markdown: false

### Front
Was ist sind die <b>zentralen Probleme</b> der
<b>SAXPY-Implementierung</b> bei <b>sequenziellen Prozessoren</b>?
<div>
  Siehe nachfolgender Code:
</div>
<div><img src=
"paste-7aacc20037c7e95eaa4011f94182bcd226a8490a.jpg"></div>

### Back
<ul>
  <li>Schleife wird vielfach durchlaufen bis Abbruchkriterium
  erreicht.
  <li>In jedem Schleifendurchlauf werden die Elemente von X und Y
  addiert und Berechnung wird das Ergebnis gespeichert.
  <li>Adressberechnung für jedes Element erforderlich.
  <li>Einzelne Operationen benötigen ggf. mehrere Zykylen
  (Multi-Zyklusoperationen)
  <li>Beachte Konflikte aufgrund von Datenabhängigkeiten
  <li>Pipeline-Stalls können durch Compiler-Optimierungen wie
  Loop-Unrolling und Software-Pipelining reduziert werden.
</ul>
