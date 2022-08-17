## Note
nid: 1592132651644
model: Basic-d7a3e
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Was versteht man unter <b>dezentralisierter Governance</b> bei
<b>Microservices</b>?

### Back
<ul>
  <li>Entwickler von Microservices ziehen es vor, hilfreiche Tools
  zu entwicklen, die andere Entwickler nutzen können, um ähnliche
  Probleme zu lösen.
  <li>Diese Tools werden von anderen Implementierungen verwendet.
  <li>Die Verwendung von Patterns wie Tolerant Reader (wenn ich
  etwas meine Schnittstelle anpasse, sollen möglichst andere
  Komponenten nicht angepasst werden), oder Consumer-Driven
  Contracts erlaubt die unabhängige Weiterentwicklung von
  Microservices.
</ul>
