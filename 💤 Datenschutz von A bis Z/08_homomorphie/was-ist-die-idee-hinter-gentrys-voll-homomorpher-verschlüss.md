# Note
```
guid: I^)8dTnud/
notetype: Basic-9c783
```

### Tags
```
datenschutz::08-homomorphe-verschluesselung
```

## Front
Was ist die <b>Idee</b> hinter <b>Gentry's voll homomorpher Verschlüsselung</b>?

## Back
Man nutzt eine Falltürfunktion. Diese expandiere ein Bit auf viele Bits mit einer Funktion, für die eine Umkehrfunktion existiert (Symmetrische Verschlüsselung). 

Füge Rauschen hinzu. Das Rauschen macht das Problem "hart", und verhindert Erraten/Ausprobieren der Parameter der Umkehrfunktion.

Man unterscheidet <i>Somewhat Homographic Encryption</i> und <i>Full Homographic Encryption</i>, je nachdem wie mit Rauschen umgegangen wird beim mehreren Operationen.
