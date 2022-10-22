# Note
```
guid: dW7Ho-prmS
notetype: Basic-b122e-20a86
```

### Tags
```
3_6_synchronisation_und_kommunikation
```

## Front
Was ist eine Schlossvariable? Welche Aufgabe verfolgt sie?

## Back
Regelt den <b>Zugang zu kritschen Abschnitten</b>, versieht diese
mit einem <b>Schloss</b>, das von Prozessoren aufgesperrt und
zugesperrt werden kann.
<div>
  Eine Schlossvariable ist eine abstrakte Datenstruktur, auf die
  alle Prozesse zugreifen müssen, die kritische Abschnitte betreten
  wollen.
</div>
<div>
  Schlossvariable verfügt über <b>lock</b> und
  <b>unlock-Methode</b>. Die Unlock-Operation kann nur von dem
  Prozess ausgeführt werden, der das Schloss vorher verschlossen
  hat.
</div>
