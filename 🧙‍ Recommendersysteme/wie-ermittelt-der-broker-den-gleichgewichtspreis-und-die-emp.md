# Note
```
guid: Jcf^40acB&
notetype: Basic-b122e-20a86
```

### Tags
```
06_wert_v_empfehlungen
```

## Front
Wie ermittelt der Broker den Gleichgewichtspreis und die Empfehlungsanzahl \(n\) aus dem Zahlungsplan?

## Back
<ol>
  <li>Spieler werden aufsteigend nach ihren Vorteilen sortiert.
  <li>Spieler wechseln von Gruppe der Wartenden in Evaluatoren
  beginnend mit den Spielern mit kleinsten Vorteilen. Solange wie
  Zuwachs der Vorteile der Abwartenden größer ist als Vorteil des
  in Gruppe der Evaluatoren wechselnden Spielers.
  <li>Der "letzte Preis" ist dann der Gleichgewichtspreis. Anzahl
  der Evaluatoren die Empfehlungsanzahl \(n\).
</ol>
