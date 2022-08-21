## Note
nid: 1627560902142
model: Basic-d7a3e
tags: 10_verbindungsstrukturen
markdown: false

### Front
Welche Schritte sind notwendig für das <b>Senden</b>, den
<b>Empfang</b> und die <b>Reaktion einer Bestätigung eines
Pakets</b>?

### Back
<div>
  <b>Senden:</b> Kopieren Daten in Puffer des NI, Aufteilen in
  Pakete, Hinzufügen von Header und Trailer, Berechnen der
  Prüfsummer, Verschicken des Pakets.
</div>
<div>
  <b>Empfang:</b> Ablage Systempuffer, Berechnung Prüfsumme,
  Versand Bestätigung, wenn korrekt sonst Löschung, Zusammensetzung
  der Nachricht und Kopieren in Puffer des Benutzerprogramms
</div>
<div>
  <b>Reaktion auf Bestätigung:</b> Wenn Bestätigung vorhanden,
  Löschen der Kopie des Pakets aus Puffer. Wenn keine Rückmeldung
  bis Time-Out, erneutes Versenden.
</div>
