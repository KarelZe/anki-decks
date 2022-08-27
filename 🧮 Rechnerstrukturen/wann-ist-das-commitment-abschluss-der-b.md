## Note
nid: 1628189707879
model: Basic-d7a3e-4ce08
tags: 06_para_maschinenbefehl
markdown: false

### Front
Wann ist das Commitment (Abschluss der Bearbeitung der Befehle) in einer superskalaren Pipeline erreicht? Nennen Sie 4 Bedingungen.

### Back
<div>
  <div>
    <ul>
      <li>Die Befehlsausführung ist vollständig
      <li>Alle Befehle, die in der Programmordnung vor dem Befehl
      stehen, haben breits ihre Bearbeitung beendet oder beenden
      ihre Bearbeitung im selben Takt
      <li>Der Befehl hängt von keiner Spekulation ab
      <li>Keine Unterbrechnung ist vor oder während der Ausführung
      aufgetreten
    </ul>
  </div>
</div>
