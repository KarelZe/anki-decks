# Note
```
guid: n_O|BjbFLQ
notetype: Basic-9c783
```

### Tags
```
angreifer
datenschutz::06_private_db
temp
```

## Front
Wie funktioniert die <b>naive Lösung</b> einer <b>von verschlüsselten Attributen</b> auf dem Server des Betreibers? Warum ist sie <b>ungeeignet</b>?

## Back
Client verschlüsselt Daten attributweise
Anfragen werden transformiert z. B. 
SELECT PLZ FROM db WHERE Name = 'Alice' wird zu 
SELECT CYM FROM db WHERE Anzr = 'Nyvpr'
Client entschlüsselt Anfrageergebnisse.

<b>Angriffe durch Zuordnung</b> möglich. Ausprobieren, ob man den Klartext erraten kann. z. B. könnte man Klartext über Public Key verschlüsseln und dann abgleichen.
<i>Beispiel:</i>
Befindet sich "Alice" in der verschlüsselten DB?

<b>Frequenzangriffe</b> möglich. Aus der Verteilung der Ciphertexte kann man auf den Inhalt schließen.
<i>Beispiel: </i>Hat "Alice" in verschlüsselter DB Urlaub genommen?

<b>Visualisierung:</b>
<img src="paste-f98192952d3b9f19f5ba82a9bb7f6410a294de02.jpg">
