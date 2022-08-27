## Note
nid: 1592743125639
model: Basic-d7a3e-4ce08
tags: 05_modelling_quality, performance
markdown: false

### Front
Wie funktioniert grob gesagt eine <b>Warteschlange</b>?

### Back
<div>
  Eine <b>Warteschlange</b> <i>(queue)</i> besteht aus einer
  Warte-Schlange (<i>waiting line</i>) und einem oder mehrerer
  Server. Jobs, welche die Warteschlange erreichen werden entweder
  sofort bedient, sofern min. einer der Server frei ist oder in die
  Warteschlange eingereiht.
</div>
<div>
  Server arbeitet die Jobs ab.
</div>
<div>
  Es gibt jeweils eine Verteilungsfunktion wie lange Server
  braucht, den Job abzuarbeiten und wie viele Jobs ankommen.
</div>
<div><img src=
"paste-ced6e61c6f9d1a4c18d6c430fdcd4c651a6639ce.jpg"></div>
<div>
  <b>Exkurs</b>:
</div>
<div>
  Eine zentrale Warteschlange ist bei mehreren Servern besser als
  einzelne Warteschlangen wegen Leerlaufen bzw. Entscheidung unter
  Unsicherheit z. B. braucht Vordermann ausgesprochen lang. Mit
  zentraler Warteschlange besteht Unsicherheit nicht.
</div>
