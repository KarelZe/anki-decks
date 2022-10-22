# Note
```
guid: tXne|&NhS!
notetype: Basic-02d89-e0e22
```

### Tags
```
05_bewertung
derivate::05_bewertung
```

## Front
Wie lassen sich amerikanische Calls im Black/Scholes Modell bewerten?

## Back
<ul><li>Ohne Dividende gilt \(C^{e}=C^{a}\)</li><li>Mit sicherer Dividende: Ausübung nur <b>unmittelbar vor Dividendentermin</b> optimal. Bestimmung über das Maximum der europäischen Callwerte \(C^{a}=\max \left\{C^{e}\left(t_{1}\right), \ldots, C^{e}(T)\right\} \rightarrow\) vorzeitige Ausübung i.d.R. entweder vor letztem Dividendentermin optimal oder gar nicht \(C^{a} \approx \max \left(C^{e}\left(t_{n}\right), C^{e}(T)\right)\).</li><li>Bei unsicherer Dividende sind numerische Methoden notwendig. Keine geschlossene Lösung vorhanden.</li></ul>
