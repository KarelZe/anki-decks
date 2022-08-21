## Note
nid: 1589728966813
model: Basic-d7a3e
tags: 02_Architectural_Viewpoints
markdown: false

### Front
Welche <b>Konnektoren</b> (<i>Connectors</i>) existieren für <b>Assemblies</b> in Paladio?

### Back
<img src="paste-52defe00724c37e809e8d6dfe539232839c2e319.jpg">
<div>
  <b>Delegation Connector:</b> Ein delegation connector wird
  genutzt um das Interface einer composite strcture mit meinem
  interface eines Assembly Kontexts in einer Verbundstruktur zu
  verbinden.
</div>
<div>
  <b>Assembly Connector:</b> Wird gebraucht um die Schnittstelle
  eines Assembly Contexts zu einer provided Schnittstelle eines
  zweiten Assembly Kontextes zu verbinden z. B. zwischen DB und
  MediaManagement Assembly.
</div>
<div>
  Assembly conncectors sind keine first-class entities in Palladio,
  weil sie keine Funktion enthalten und nur weiterleiten. Sollen
  sie Funktionen enthalten müsste man sie als Komponente
  modellieren.
</div>
