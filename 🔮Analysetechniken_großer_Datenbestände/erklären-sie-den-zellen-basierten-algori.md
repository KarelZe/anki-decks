## Note
nid: 1632902538885
model: Basic-d7a3e
tags: 10_id_von_outliern, checklater, ultra
markdown: false

### Front
Erklären Sie den Zellen-basierten Algorithmus für das Finden von Outliern.

### Back
<ul>
  <li>\(k\)-dimensionaler Raum wird partitioniert in würfelförmige
  Zellen der Länge \(D / 2 \sqrt{k}\), wobei k die Dimensionalität
  angibt.
  <li>Wir prüfen nicht für jedes Objekt einzeln, sondern
  <b>gesamthaft für die Zelle</b>
    <ul>
      <li>Handelt es sich für die Objekte in der Zelle gesamthaft
      um Outlier oder nicht?
      <li>Einzelne Objekte müssen nicht mehr betrachtet werden.
      <li>Bei Häufungen mit vielen Objekten in Zellen hat man eine
      Beschleunigung ggü. Einzelbetrachtung erreicht.
    </ul>
</ul>
<div>
  <strong>L1-Nachbarschaft</strong>: alle direkten Nachbarn
  (hellrot unten) / Zellen, die Minkowski Summe vollständig
  einschließt
</div>
<ul>
  <li>Test, ob betrachtete Objekte in Zelle <span style= 
  "text-decoration-line: underline;"><strong>keine</strong>
  <strong>Ausreißer</strong></span> sind
  <li>L1 liegt immer komplett in Radius von D. L1 ist die
  betrachtete Zelle + die unmittelbar umgebenden Zellen.
  <li>Liegen in roter Fläche d. h. L1 zu viele Punkte für
  Outlierness, dann liegen auch innerhalb der Kugel zu viele
  Objekte für Outlier. Damit sind Punkte in gelber Zelle <b>keine
  Outlier.</b>
  <li>Zellen mit <b>mehr</b> als \(m = 1-p\) Tupeln in
  L1-Nachbarschaft enthalten keine Outlier, brauchen also nicht
  weiter betrachtet werden.
</ul>
<div>
  <div>
    <strong>L2-Nachbarschaft</strong>: Zellen, die Minkowski Summe
    berührt
  </div>
  <ul>
    <li>Test, ob betrachtete Objekte in Zelle <span style= 
    "text-decoration-line:
    underline;"><strong>Ausreiße</strong></span>r sind
    <li>L2 Nachbarschaft sind die Zellen, die egal wie wir den
    Mittelpunkt in gelber Zelle wählen, eine Kugel mit Radius \(D\)
    stets enthält.
    <li>Angenommen L2 enthält so wenig Objekte, dass Zelle
    Ausreißer ist, dann kann man auch für Objekte in gelber Zelle
    sagen, dass es sich mit Sicherheit um einen Ausreiser handelt.
    <li>Zellen mit <b>weniger</b> als \(m = 1-p\) Tupeln in
    L2-Nachbarschaft enthalten nur Outlier.
  </ul>
  <div>
    Schlägt keiner der beiden Tests an, müsste man eine
    Komplettbetrachtung machen z. B. mit nested loop Ansatz.
  </div>
  <div><img src=
  "406567_BiLaYuNaxoyoluke2268298763131673.png"></div>
</div>
