# Note
```
guid: QTV!PJ2y1r
notetype: Basic-9c783
```

### Tags
```
datenschutz::06_private_db
temp
```

## Front
Erklären Sie das <b>Systemmodell</b> von <b>Bucketization</b>. Was
macht der <b>Server</b>? Was der <b>Client</b>?

## Back
<b>Server:</b> Datenbank db mit Relationenschema \(R\), tupelweise
verschlüsselt: enc \(=\operatorname{encode}\left(\left\{A_0,
\ldots, A_n\right\}\right), A_0, \ldots, A_n \in R\) kodierten
Index. <b>Client:</b> Transformeirt <b>Anfragen für verschlüsselte
Repräsentationen</b>, <b>entschlüsselt</b> Zwichenergebnisse vom
Server und <b>berechnet Endergebnisse</b>. <img src="paste-87f259f26aeef2a0326c18a97773bed453f73860.jpg">
