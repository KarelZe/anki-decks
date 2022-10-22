# Note
```
guid: N=TS{.We.Y
notetype: Basic-9c783
```

### Tags
```
angreifer
datenschutz::06_private_db
```

## Front
Welcher <b>Tradeoff</b> besteht zwischen <b>Performance</b> und <b>begrenzter Offenlegung</b> bei Datenbanken?

## Back
<b>Gute Sicherheit:</b>
<ul><li>Starke Verschlüsselung ist aufwendig z. B. Schlüsselmanagement, Authentifizierung</li><li>Hoher Aufwand gegen Frequenz- und Rate-Angriffe z. B. kann Dienstleister mitloggen</li><li>Client muss festlegen, welche Informationen offenbart werden dürfen</li></ul>
<b>Gute Performanz:</b>
<ul><li>Erzwingt einfache Verfahren, Risiko für Offenlegung steigt</li><li>Anfrageausführung soll auf dem Server erfolgen</li><li>Möglichst kleine Zwischenergebnisse zum Client schicken</li></ul>
