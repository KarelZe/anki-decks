# Note
```
guid: HUYu}x}*j`
notetype: Basic-9c783
```

### Tags
```
datenschutz::06_private_db
```

## Front
Wie funktioniert die <b>naive Lösung</b> einer <b>großen, verschlüsselten Datenbank</b> auf dem Server des Betreibers? Warum ist sie <b>unpraktikabel</b>?

## Back
Client verschlüsselt die gesamte Datenbank und sendet diese an den Server. Client entschlüsselt Anfrageergebnisse immer lokal.
Serverbetreiber erhält einen großen, verschlüsselten Datenblock.

Unpraktikabel, weil immer der vollständige Datensatz zum Client geschickt und dort entschlüsselt wird.

<b>Visualisierung:</b>
<img src="paste-0890d80fd68124841d7abf99f79712d53432c7e0.jpg">
