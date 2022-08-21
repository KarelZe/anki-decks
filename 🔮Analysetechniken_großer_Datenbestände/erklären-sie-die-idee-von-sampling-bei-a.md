## Note
nid: 1632812925299
model: Basic-d7a3e
tags: 07_association_rules
markdown: false

### Front
Erklären Sie die <b>Idee </b>von <b>Sampling </b>bei <b>Apriori</b>.

### Back
Man wählt zunächst einen möglichst repräsentativen Teil des
Gesamtdatenbestands aus.
<div>
  Dann erzeugt man sich darauf die sukzessive größere Itemsets bis
  Itemsets nicht mehr frequent sind. Der Bereich, ab dem Itemsets
  nicht mehr frequent sind bzw. gerade noch maximal frequent sind,
  nennt man negative border. Man ist nur an maximalen frequent
  Itemsets interessiert.
</div>
<div>
  Wann die <i>negative border</i> erreicht wird, hängt vom
  erforderlichen Support ab. Der Support wird ggü. dem Support des
  Gesamtdatenbestands verringert bzw. erhöht, sodass man eine Art
  Schlauch erhält.
</div>
<div>
  Dann wird die negative border mit einem Scan über die Datenbank
  überprüft. Hierbei wird Gesamtdatenbestand und exakter
  Mindestsupport berücksichtigt.
</div>
<div><img src=
"paste-fd9608e7c620ffe2a5c659b0bb28cefec035d39d.jpg"></div>
