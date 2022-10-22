# Note
```
guid: t[-%iB9:FX
notetype: Basic-d7a3e-4ce08
```

### Tags
```
04_koheraenz
```

## Front
Wie lässt sich mit atomaren Operationen in folgendem Beispiel
vermeiden, dass <b>zwei Threads</b> gleichzeitig in <b>kritischen
Bereich</b> eintreten?
<div><img src="paste-ff520d8d7dde42bee11ef6aecec3cb2cd89b4ccd.jpg"></div>

## Back
Nicht <b>unterbrechbare (atomare) Read-Modify-Write-Operation
(RMW)</b> liest einen Wert aus dem Speicher, ändert ihn und
schreibt ihn wieder in Speicher zurück, ohne dass ein anderer
Prozessor darauf zugreifen kann.
