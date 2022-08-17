## Note
nid: 1609430840746
model: Basic-d7a3e
tags: 03_raeumliche_index_strukturen, checklater
markdown: false

### Front
<p>

Wie findet man bei <b style="font-weight:700;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px">Nearest-Neighbour-Anfragen </b>alle<b style="font-weight:700;letter-spacing:0.12852px;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px"> </b>Datenobjekte innerhalb des Bereichs bei einem <b>kd-Baum</b>?


</p>

### Back
<p><img src="paste-35d348858451bc145a8e7eb87be68cd163c84f32.jpg">
<p>Man legt um den Anfragepunkt eine Kugel (<i>nearest neighbour
sphere</i>), bis man den nächsten Datenpunkt erreicht. Innerhalb
der Kugel liegen keine Datenobjekte!
<p>Man durchsucht diese mit einer <b>Priority-Queue</b>.
<p><span>Man entnimmt zunächst den Wurzelknoten und ersetzt ihn
durch seine Kindobjekte, Objekte werden mit Abstand zum
Anfragepunkt in Queue eingeordnet. Grüner Knoten hat geringeren
Abstand. Dann werden Kinder des Knoten in Priority-Queue eingefügt.
Abstand zu Blau ist wieder geringer als die Kind-Elemente von Grün.
Deshalb werden Datenobjekte aus Blattknoten in Queue eingeordnet.
Objekte links davon ist größer als Abstand des Rechtecks, worin sie
enthalten sind. (Untere Schranke des Abstands). Braucht also nicht
ausgewertet werden!</span>
<p><span>Vorteil ist, dass nicht jeder Datenpunkt (wie bei einem
naiven Ansatz) verglichen werden muss, sondern nur in bestimmten
Zonen / ausgewählten Rechtecken, die durch den kd-Baum gegeben
sind.</span>
