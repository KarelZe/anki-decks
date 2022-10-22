# Note
```
guid: M(-8qvP7Au
notetype: Basic-9c783
```

### Tags
```
datenschutz::04-internetprotokolle
```

## Front
Wie werden Daten <b>referenziert</b> bei <b>Freenet</b>?

## Back
Zwei relevante Schlüsseltypen:
<ul>
  <li><b>Content-hash key:</b> kryptische Signatur der Daten, z.
  B.: CHK@SVbD9[...]4yFCB,bA7qLNJ[...]8kSi6bbNQ,AAEA--8
  vergleichbar mit <b>Inodes im Dateisystem</b>
  <li><b>Signed-subspace key:</b> Namespaces, in denen jeder lesen,
  aber nur der Ersteller schreiben kann z. B:
  SSK@GB3wu[..]o-eHK35w,c63Ez[..]3YDduXDs,AQABAAE/mysite-4
  vergleichbar mit <b>Datei- und Verzeichnisnamen</b>: Updatable
  Subspace Key verweist immer auf den aktuellsten
  SSK@GB3wu[..]o-eHK35w,c63Ez[..]3YDduXDs,AQABAAE/mysite-4
  <b>Updatable Subspace Key</b> spart die Mühe, nach der jünsten
  Version eines SSK suchen zu müssen
</ul>Verbreitung der Schlüssel als Lesezeichen 🔖, in öffentlichen
Directories oder über Freenet-Suchmaschinen
