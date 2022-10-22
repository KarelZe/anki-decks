# Note
```
guid: O6Za1bC>A=
notetype: Basic-d7a3e-4ce08
```

### Tags
```
02_vorlesung
```

## Front
<p>Was sind die Vorteile und Nachteile der Asynchronen Methode (d.
h. ignorieren von Abhängigkeiten zwischen Gitterpunkten) bei der
OCEAN-Simulation.

## Back
<p>- Ignorieren der Abhängigkeiten zwischen den Gitterpunkten für
einen Durchlauf
<p>- Globale Synchronisation zwischen den Iterationen, aber keine
Änderung der Durchlaufordnung.
<p>- Punkte können auf mehrere Prozesse aufgeteilt werden.
<p>- Ausführung ist <b>nicht deterministisch</b>!
<p>- Anzahl der Durchläufe bis zur Konvergenz kann von der Anzahl
der Prozesse abhängen.
