# Note
```
guid: <-8sk8QO3
notetype: Basic-d7a3e-4ce08
```

### Tags
```
12_Vektorverarbeitung
```

## Front
Wie wird das Problem gelöst, dass der Vektor-Stride-Wert z. B. \(3\) erst zur Laufzeit bekannt wird und sich verändern kann?

## Back
<div>
  <div>
    <ul>
      <li>Der Stride-Wert wird selbst in Allzweck-Registern
      abgelegt
      <li>Vektorspeicherzugriffsbefehle greifen dann auf Wert zu.
      <li>Problem dabei ist, dass Zugriff auf Speicherbank häufiger
      erfolgt als Zugriffszeit der Bank es erlaubt → Der Zugriff
      von jedem Prozessor wird über mehrere hundert Speicherbänke
      verteilt.
    </ul>
  </div>
</div>
