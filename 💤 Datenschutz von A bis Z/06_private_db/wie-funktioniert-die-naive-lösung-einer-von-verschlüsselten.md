# Note
```
guid: vm,W4Cfg/S
notetype: Basic-9c783
```

### Tags
```
datenschutz::06_private_db
temp
```

## Front
Wie funktioniert die <b>naive Lösung</b> einer <b>von verschlüsselten Tupeln</b> auf dem Server des Betreibers? Warum ist sie <b>unpraktikabel</b>?

## Back
Client verschlüsselt Daten zeilenweise (jedes Tupel für sich), bevor sie auf dem Server gespeichert werden. Client entschlüsselt dann die Anfrageergebnisse.

Unpraktikabel, weil sehr eingeschränkte Anfragemöglichkeit z. B. gib mir die 2., 3., und 6. Zeile aus der Datenbank zurück. Entschlüsselung und jede Art von Operation erfolgt dann auf dem Client.

<img src="paste-2bf36df546df2c4107a3791a7c6fc580fc62ada8.jpg">
