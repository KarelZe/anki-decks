# Note
```
guid: Gv5[9CDSLf
notetype: Basic-9c783
```

### Tags
```
datenschutz::02_encryption
```

## Front
Erklären Sie wie Advanced Encryption Standard (AES) funktioniert.

## Back
AES ist eine ist ein symmetrisches Verschlüsselungsverfahren.
Findet Verwendung bei WLAN (WPA2), SSH, HTTPS... AES verschlüsselt
blockweise (Blockchiffre). <b>Aufbau:</b> Die Schlüssel haben eine
Länge von 128, 192 oder 256 Bit. Ein Block ist eine Tabelle mit 4
Zeilen und 4 Spalten und 1 Byte pro Zelle. (-> 128 Bit)
<b>S(ubstitution)-Boxen:</b> SubBytes (Byte in Tabelle wird in
anderes Byte in der S-Box ersetzt / ähnlich Lookup)
<b>P(ermutation)-Boxen:</b> ShiftRows (Verschieben der Zelle um
Nummer seiner Zeile), Mix Columns (Spaltentausch in Matrix)
<b>AddRoundKey:</b> Bitwise XOR-Verknüpfung von einem Block und dem
Rundenschlüssel (Auch 4 Zeilen und 4 Spalten). Es ist die einzige
Stelle, wo <b>Schlüssel angewendet</b> wird. Andere Operationen
sind von Eingabedaten abhängig. <b>Visualisierung:</b> <img src="paste-b40e92b4eeb05201c0de5d0421d738534f131fdb.jpg"> <i>SubBytes
in S-Boxen z. B. 12 wird zu c9: <img src="paste-54c2f5871fa883b04e02ebc8b7bbaa32f7b81ca4.jpg"> Shift
Rows:</i> Jede Zelle um Nummer seiner Zeile nach links verschieben.
Links herausfallende Zellen rechts einfügen. <img src="paste-6a62d1fb5c9a1e5042654f2fea65b5801181e6ed.jpg">
<i>MixColumns:</i> Entspricht Matrix-Multiplikation <img src="paste-d6175aaadd618ffa5ded547147a9e546961254c1.jpg">
<i>AddRoundKey:</i> Bitweise XOR-Verknüpfung von einem Block und
dem Rundenschlüssel. <img src="paste-08663fa9169311e6e0f14dbca5f8ea0bd7cbec8e.jpg">
