## Note
nid: 1592335351187
model: Basic-d7a3e-4ce08
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Was sind in der Clean Architecture <b>Entities</b>, <b>Use
Cases</b> und <b>Interface Adapters</b>?
<div><img src=
"paste-779a4f0c79c1acc4ded9362c5f1e0a0cc007ccf2.jpg"></div>

### Back
<p><strong>Entities</strong>
<ul>
  <li>Kapseln Business-Regeln <em>z. B. Objekte mit Methoden,
  Datenstrukturen mit Funktionen</em>
  <li>Können als Business-Objekte für Anwendungen verwendet werden.
  <li>Entität ist vergleichsweise stabil ggü. externen
  Veränderungen.
  <li>Ändert sich Entität, so hat man eine andere Anwendung z. B.
  keine Mahnwesen-Anwendung mehr, wenn keine Rechnung.
</ul>
<p><strong>Use-Cases</strong>
<ul>
  <li>Enthalten Architektur-spezifische Business-Regeln
  <li><b>Implementiert Use Cases eines Systems</b> <em>d. h.
  Datenströme von und zu Enititäten</em>
  <li>Dieser Layer sollte nur getauscht werden, wenn sich die
  operationellen Anforderungen verändern z. B. andere Use Cases ,
  sodass Code des Use-Case Layers editiert werden muss. Nicht aber
  bei Veränderungen am Framework.
</ul>
<p><strong>Interface Adapters</strong>
<ul>
  <li>Hauptaufgabe ist der Datenaustausch zwischen Schichten.
  <ul>
    <li>Adaptiert Interfaces für den <em>Use Case Layer</em> und
    externe Interface Layer
    <li>Datenkonvertierung zwischen Uses Cases des Systems und
    externen Agenten z. B. Datenbanken oder UI
  </ul>
</ul>
<div>
  <b>Dependency Rule</b>
</div>
<div>
  Abhängigkeiten im Quellcode zeigen nach innen. Regel gilt für
  Funktionen, Klassen, Variablen und Datenformate.
</div>
