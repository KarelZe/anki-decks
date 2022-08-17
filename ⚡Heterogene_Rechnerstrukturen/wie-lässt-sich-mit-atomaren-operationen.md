## Note
nid: 1613215362984
model: Basic-b122e
tags: 04_koheraenz
markdown: false

### Front
Wie lässt sich mit atomaren Operationen in folgendem Beispiel vermeiden, dass <b>zwei Threads</b> gleichzeitig in <b>kritischen Bereich</b> eintreten?<div>
</div><div><img src="paste-ff520d8d7dde42bee11ef6aecec3cb2cd89b4ccd.jpg">
</div>

### Back
Nicht <b>unterbrechbare (atomare) Read-Modify-Write-Operation (RMW) </b>liest einen Wert aus dem Speicher, ändert ihn und schreibt ihn wieder in Speicher zurück, ohne dass ein anderer Prozessor darauf zugreifen kann.
