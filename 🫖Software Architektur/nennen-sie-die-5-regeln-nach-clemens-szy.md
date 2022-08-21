## Note
nid: 1590514682583
model: Basic-d7a3e
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Nennen Sie die 5 Regeln nach Clemens Szyperski zur Identifikation von Komponenten inkl. eines Beispiels.

### Back
<ol>
  <li>Components should be entities of reuse. Z<i>. B.
  Wiederverwendung innerhalb derselben Produktlinie,
  Produktfamilie, in verschiedenen Kontexten und vielen
  verschiedenen Kontexten z. B. als Bibliotheksfunktion.</i>
  <li>Components should be entities of update / maintenance.
  <b>Intuition:</b> Selbst wenn ich es gar nicht wiederverwende in
  anderen Systemen, möchte ich es trotzdem kapseln, um das derzeit
  betrachtete System wartbar zu halten. <b>Beispiele:</b> What has
  to be updated because of frequent technical changes, frequent
  requirement changes z. B. Steuerbrechnung, interoperability with
  other systems, different alternatives z. B. Scheduling
  Strategien.
  <li>Components should be entities of dynamic reconfiguration.
  <b>Beispiele:</b> What has to be dynamically be swapped in and
  out due to memory limitations z. B. Apps auf Handys or frequent
  software updates z. B. Bios
  <li>Components should be entities of distribution (on a lower
  level). <b>Intuition:</b> Komponenten sind deployment units.
  <b>Beispiele:</b> What has to be distributed on different
  computers, due to natural distribution z. B. reservation systems,
  parallelisation z. B. master-worker processes, fault-tolerance z.
  B. control software.
  <li>Components should be entities of delivery / accounting.
  <b>Beispiele:</b> what should be delivered / updated seperately,
  because of specialised functionality, different versioning, extra
  functionality, business service definition, organisational
  boundaries.
</ol>
