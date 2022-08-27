## Note
nid: 1592124880702
model: Basic-d7a3e-4ce08
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Was sind die <b>Vor-und Nachteile</b> einer <b>Event-basierten
Architektur</b>?

### Back
<p><strong>Vorteile</strong>
<ul>
  <li>Klingt verlockend einfach z. B. ist Bus einfach gezeichnet.
  <li>Es wird scheinbar keine Architektur benötigt.
</ul>
<p><strong>Nachteile</strong>
<ul>
  <li>Das Systemverhalten ist <strong>schwer zu verstehen</strong>
  und zu <strong>extrapolieren</strong> z. B. was passiert wenn
  Komponente Nachricht nicht verarbeiten kann? Bzw. häufig schlecht
  verhersagbar, was unter Last passiert.
  <li>System ist oft <strong>nicht deterministisch.</strong>
  (Abhängigkeiten zwischen Events brauchen ggf. globale Zeit)
  <li>Skaliert schlecht. (Event-Bus ist nicht deterministisch)
</ul>
