# Note
```
guid: H^5xkOhFoI
notetype: Basic-9c783
```

### Tags
```
datenschutz::02_encryption
```

## Front
Wie funktioniert der <b>Cipher Feedback Mode</b> bei
<b>Blockverschlüsselung</b>?

## Back
Initialisierungsvektor wird verschlüsselt. Jeder Klartext-Block
wird per XOR mit dem Cipher-Block verkettet. Die ausgegebenen
Geheimtextdaten fließen als Eingabe in den nächsten Block zur
Verschlüsselung. Jeder Block ist damit der Initialisierungsvektor
des Folgeblocks. <b>Vorteil:</b> Selbstsynchronisation d. h.
Empfänger muss nicht den genauen Inhalt des Blocks zur
Entschlüsselung kennen. <b>Nachteil:</b> Ein Bitfehler zerstört den
betreffenden Block. <b>Visualisierung:</b> <img src="paste-3a8059a197c72ed1ebd8f2b22912d08ebc7d4b81.jpg">
