# Note
```
guid: yCP#Z+x.^t
notetype: Basic-9c783
```

### Tags
```
datenschutz::04-internetprotokolle
```

## Front
Erklären Sie die <b>Freenet-Architektur</b>. Welche
<b>Komponten</b> existieren und wie werden <b>Daten adressiert</b>
bzw. <b>abgerufen</b>?

## Back
<ul>
  <li>Jeder Knoten speichert Daten und die Routing-Tabelle mit
  ausgewählten Knoten.
  <li>Daten werden über einen ortsunabhängigen Schlüssel
  referenziert. Häufig genutzte Daten werden repliziert, wenig
  genutzte aus den Caches gelöscht.
  <li>Anfragen mit Schlüssel werden über Freenet-Knoten
  verschlüsselt geroutet. Routing Topologie lernt dazu.
</ul>
