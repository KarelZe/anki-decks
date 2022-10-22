# Note
```
guid: gbfQ5(KZ$z
notetype: Basic-9c783
```

### Tags
```
datenschutz::06_private_db
temp
```

## Front
Erklären Sie das Konzept einer sicheren Middleware. Wer sind die Akteure und welche Aufgaben haben sie?

## Back
<img src="paste-dbf56eedf91c48d272203f299474183b7d8c0100.jpg"><b>

Client</b> macht <b>Query Rewriting t</b>ransformiert also Klartext-SQL auf verschlüsselte Anfragen und sendet die and den Provider
Provider führt Anfrage aus, liefert kodiert Zwischenergebnisse zurück.
<b>Client</b> macht mit <b>Query Rewriting</b> Rücktransformation von verschlüsselten Ergebnissen. Client ermittelt endgültiges Anfrageergebnis aus Zwischenergebnis.
