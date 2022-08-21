## Note
nid: 1628397876165
model: Basic-d7a3e
tags: checklater, klausur
markdown: false

### Front
Geben Sie die die Formel für die maximale Beschleunigung \(S\) bei Verwendung einer skalaren Pipeline an und begründen Sie unter welchen Umständen diese Beschleunigung erreicht werden kann.

### Back
<div>
  <b>Speedup</b> \(S\):
</div>
<div>
  \(S=\frac{n * k}{n+k-1}\)
</div>
<div>
  <div>
    mit \(n\): Anzahl der Befehle in einem Programm (Annahme:
    ideale Verhältnisse!) und \(k\) : Anzahl der Ausführungsphasen.
  </div>
</div>
<div>
  Diese Beschleunigung kann nur unter Annahme idealer Verhältnisse
  erzielt werden, d. h. in jedem Takt kann ein Befehl geholt bzw.
  beendet werden.
</div>
