# Note
```
guid: oW,T#uKA]!
notetype: Basic-9c783
```

### Tags
```
datenschutz::02_encryption
```

## Front
Was sind die <b>Vor- und Nachteile</b> von <b>RC4</b>?

## Back
<b>Nachteile:</b>
<ul>
  <li>Keine Garantie von Integrität. Wird nur ein Bit im
  Cipher-Strom verändert, dann verändert sich dasselbe Bit im
  Klartext.
  <li>Mit einer Chosen-Plaintext-Attacke lässt sich der
  Schlüsselstrom aus der S-Box enthüllen. Deshalb niemals den
  Schlüssel mehrmals verwenden.
</ul>
