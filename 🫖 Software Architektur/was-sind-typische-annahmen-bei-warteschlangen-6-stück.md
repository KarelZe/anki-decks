# Note
```
guid: fX2UjFe*0:
notetype: Basic-d7a3e-4ce08
```

### Tags
```
05_modelling_quality
performance
```

## Front
Was sind <b>typische Annahmen</b> bei Warteschlangen? (6 Stück)

## Back
<ul>
  <li><b>Infinite population assumption:</b> Der Pool der User ist
  so groß, dass die arrival rate unabhängig von den vorherigen
  Anfragen ist.
  <li><strong>Homogeneous workload assumption:</strong> Alle
  Anfragen lassen sich statistisch nicht unterscheiden d. h. nur
  die Zahl der Anfragen ist wichtig, nicht aber die individuelle
  Anfrage
  <li><strong>Infinite queue assumption:</strong> Keine Anfrage
  wird abgelehnt und alle ankommenden Requests werden eingereiht
  für einen Dienst.
  <li><strong>Finite queue assumption</strong>: Die Größe der Queue
  ist endlich und ankommende Anfragen müssen abglehnt werden,
  sofern die Queue voll ist.
  <li><strong>Operational equilibrium assumption:</strong> Die
  Anzahl der Anfragen zu Beginn des Beobachtungsinteralls und am
  Ende ist ungefähr gleich. Insbesondere bei großen Systemen.
  <li><strong>Markovian assumption:</strong> Das System hat kein
  Gedächtnis d. h. das zukünftige Verhalten des Systems ist nur
  abhängig vom Zustand, in dem es sich gerade befindet und nicht
  wie es diesen erreicht oder wie lange es dort verbleibt.
</ul>
