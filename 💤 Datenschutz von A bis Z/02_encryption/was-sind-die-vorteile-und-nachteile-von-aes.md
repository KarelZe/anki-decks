# Note
```
guid: B{GDR$B&/E
notetype: Basic-9c783
```

### Tags
```
angreifer
datenschutz::02_encryption
```

## Front
Was sind die <b>Vorteile</b> und <b>Nachteile</b> von <b>AES</b>?

## Back
<b>Vorteile:</b>
<ul>
  <li>Gute Performanz, weil billige Operationen, 128 Bit Blockgröße
  gut zu GPU / CPU-Architektur passt, Beschleuniger-Implementierung
  möglich.
  <li>AES ist sicher. Bester Angriff nur um Faktor 4 schneller als
  Brute Force.
</ul><b>Nachteile:</b>
<ul>
  <li>Braucht sicheren Kanal für Schlüsselübertragung
  <li>Viele Kommunikationspartner führt zu vielen Schlüsseln: \(S =
  \left(\begin{array}{l}N \\
  2\end{array}\right)=\frac{(N(N-1))}{2}\) z. B. \(N=5\) sind \(S =
  10\) Schlüssel
  <li>Verarbeitet nur ganze Blöcke
</ul>
