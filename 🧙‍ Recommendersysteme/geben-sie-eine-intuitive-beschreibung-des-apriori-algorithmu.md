# Note
```
guid: NJ$BP8bVY:
notetype: Basic-b122e-20a86
```

### Tags
```
02_assoziationsregeln
```

## Front
Geben Sie eine <b>intuitive Beschreibung</b> des
<b>Apriori-Algorithmus</b> an.

## Back
<ul>
  <li><strong>Schritt 1:</strong> Berechne welche Itemmengen "oft"
  in Transaktionen vorkommen. "Oft" wird durch \(s_{min}\)
  festgelegt. Dadurch werden zufällig gemeinsam gekaufte Produkte
  aus der Betrachtung ausgeschlossen und der Suchraum verkleinert.
  <li><strong>Schritt 2:</strong> Berechne, welche Teile der
  Itemmenge \((X \backslash Y)\) fast nie ohne die restlichen Teile
  der Menge (\(Y\)) gekauft werden (Konfidenz). "Fast nie" wird
  durch \(c_{\text {min }}\) festgelegt. Wir können nun einem
  Käufer einer Teilmenge von \((X \backslash Y)\) den restlichen
  Inhalt der Menge (\(Y\)) empfehlen!
</ul>
