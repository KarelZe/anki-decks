# Note
```
guid: Lfm<:}i0R#
notetype: Basic-b122e-20a86
```

### Tags
```
Eigene
```

## Front
Was unterscheidet ein <i>lock</i> von einer <i>semaphore</i>?

## Back
<ul>
  <li>Ein <strong>lock</strong> kann verwendet werden, um einem
  Thread Zugriff zu geben. Das lock wird nicht mit anderen
  Prozessen geteilt.
  <li>Eine <strong>semaphore</strong> kann verwendet werden, um
  mehreren Threads Zugriff Zugriff auf einen Codeabschnitt zu
  geben. Damit lassen sich die Anzahl der Threads mit Zugriff auf
  eine Ressource regeln. Beispiel: <em>Ein Beispiel aus dem Leben
  ist z. B. die Benutzung eines Aufzuges, in dem maximal 5 Personen
  Platz haben. Ein Semaphor wäre hier ein Zähler, der auf 5
  initialisiert wird und jedes Mal, wenn eine Person den Aufzug
  betritt, wird er um 1 herabgezählt (dekrementiert). Verlässt eine
  Person den Aufzug, dann wird der Zähler um 1 erhöht
  (inkrementiert). Ist der Zähler auf 0, so darf keine weitere
  Person den Aufzug betreten</em>.
</ul>
