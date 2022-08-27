## Note
nid: 1592133260297
model: Basic-d7a3e-4ce08
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Was versteht man unter <b>Smart Endpoints and Dumb Pipes</b> bei
<b>Microservices</b>?

### Back
<ul>
  <li>Anwendungen von Microservices sollen möglichst kohärent und
  entkoppelt sein, wie möglich.
  <li>Jeder Service verfügt über seine eigene Domänenlogik und
  fungiert als Filter <i>d. h. Nimmt Request entgegen, wenden Logik
  an und produzieren eine Antwort.</i>
  <li>Häufig umgesetzt mit einfachen Ansätzen wie REST.
  <li>Keine komplexe Kommunikations-Infrastruktur wie Bus.
</ul>
<div><img src=
"paste-c436568d1ce4093e07d08518dc48de7cf34f03c8.jpg"></div>
