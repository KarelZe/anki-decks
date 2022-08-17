## Note
nid: 1592333974389
model: Basic-d7a3e
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Was sind die Folgen von <b>Clean Architecture</b>?

### Back
<ol>
<li><b style="">Independent of Frameworks. </b>Die Architektur hängt nicht von einer bestimmten bestimmten Bibliothek oder mit Featuren beladener Software ab. </li>
<li><b>Testable. </b>Die Geschäftslogik kann ohne UI, Datenbank, Webserver oder jeder anderen Komponente getestet werden, weil man stabilen Kern hat.</li>
<li><b>Independent of UI.</b> Das UI kann schnell angepasst werden, ohne, dass man den Ret des Systems anpassen muss. Ein Web UI kann durch eine Konsole ersetzt werden, ohne dass die Businesslogik verändert werden muss.</li>
<li><b>Independent of Database.</b> Man kann die Datenbank z. B. von Oracle oder SQL Server, zu Mongo, BigTable oder CouchDB tauschen</li>
<li><b style="">Independent of any external agency. </b>Die Businessregeln wissen nicht "von der Außenwelt"</li>
</ol>
