# Note
```
guid: c4Ur2)h+/-
notetype: Basic-9c783
```

### Tags
```
angreifer
datenschutz::04-internetprotokolle
```

## Front
Was ist ein <b>Endpoints-Angriff</b> bei <b>TOR </b>und wie funktioniert er? Wie kann er gelöst werden?

## Back
Angreifer kontrolliert den ersten und letzten Knoten einer Verbindung
<img src="paste-c503358f9e4382c1e3b5806d51486f2c4184d902.jpg">

<b>Lösung:</b> 
Entry Guards.🤺 Ein Tor-Client wählt ein paar Relays zufällig als Entry Point aus und nutzt diesen bis zum ersten Knoten. Werden diese Relays nicht vom Angreifer kontrolliert, ist man sicher. Wenn kontrolliert, dann sieht der Angreifer nur mehr vom Traffic.
