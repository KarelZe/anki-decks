## Note
nid: 1627885744281
model: Basic-d7a3e-4ce08
tags: 06_para_maschinenbefehl, checklater, klausur
markdown: false

### Front
Wie lässt sich der <b>Speedup für RISC-Pipelines</b> durch
<b>Pipelining</b> eines Maschinenbefehls berechnen?

### Back
<b>Sequentielle Ausführung</b>: \(T=n * k\) <b>Parallele Ausführung
in Pipeline</b>: \(T=n+k-1\),
<div>
  mit \(n\): Anzahl der Befehle in einem Programm (Annahme: ideale
  Verhältnisse!)
</div>
<div>
  <div>
    und \(k\) : Anzahl der Ausführungsphasen
  </div>
</div>
<div>
  <b>Speedup</b> \(S\):
</div>
<div>
  \(S=\frac{n * k}{n+k-1}\)
</div>
