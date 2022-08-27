## Note
nid: 1616421146797
model: Basic-b122e-20a86
tags: 06_wert_v_empfehlungen
markdown: false

### Front
Wie ermittelt der Broker den Gleichgewichtspreis und die Empfehlungsanzahl \(n\) aus dem Zahlungsplan?

### Back
<ol>
  <li>Spieler werden aufsteigend nach ihren Vorteilen sortiert.
  <li>Spieler wechseln von Gruppe der Wartenden in Evaluatoren
  beginnend mit den Spielern mit kleinsten Vorteilen. Solange wie
  Zuwachs der Vorteile der Abwartenden größer ist als Vorteil des
  in Gruppe der Evaluatoren wechselnden Spielers.
  <li>Der "letzte Preis" ist dann der Gleichgewichtspreis. Anzahl
  der Evaluatoren die Empfehlungsanzahl \(n\).
</ol>
