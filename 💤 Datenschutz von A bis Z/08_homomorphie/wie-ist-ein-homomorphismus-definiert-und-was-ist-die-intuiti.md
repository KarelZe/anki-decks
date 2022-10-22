# Note
```
guid: LrTuH<-~b
notetype: Basic-9c783
```

### Tags
```
datenschutz::08-homomorphe-verschluesselung
```

## Front
Wie ist ein <b>Homomorphismus</b> definiert und was ist die <b>Intuition </b>dahinter?

## Back
<b>Definition:</b>
Sei M die Menge aller Klartexte und C die Menge aller Ciphertexte. Sei \(\odot_M\) und \(\odot_c\) zwei Operatoren auf Klar/Ciphertexten
Eine Encryption-Funktion \(E\) ist homomorph, wenn \(\forall \mathrm{m}_1, \mathrm{~m}_2 \in \mathrm{M}: \mathrm{E}\left(\mathrm{m}_1 \odot_{\mathrm{m}} \mathrm{m}_2\right) \leftarrow \mathrm{E}\left(\mathrm{m}_1\right) \odot_{\mathrm{c}} \mathrm{E}\left(\mathrm{m}_2\right)\)
("←" meint: Kann ohne vorherige Entschlüsselung berechnet werden)

<b>Intuition:</b>
dasselbe Ergebnis, egal ob zuerst die Klartexte miteinander verknüpft und dann verschlüsselt, oder zuerst verschlüsselt und dann die Ciphertexte miteinander verknüpft werden
