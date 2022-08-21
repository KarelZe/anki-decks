## Note
nid: 1632658968360
model: Basic-d7a3e
tags: 03_raeumliche_index_strukturen, checklater
markdown: false

### Front
Erklären Sie den <b>R-Baum</b>.

### Back
Ein R-Baum ist eine balancierte Indexstruktur, die eine schnelle
Suche nach und auf Objekten mit räumlicher Ausdehnung erlaubt.
Einzig in den Blattknoten sind Datenobjekte enthalten. Übrige
Knoten enthalten sogenannte minimum bounding rectangles, also
Rechtecke, die alle darunter im Teilbaum befindlichen Datenobjekte
einschließen. <i>Minimum bound rectangles</i> können sich
überlappen.
<div><img src=
"paste-2690c8eb47dcdf44502a097ae597fadef3b30c06.jpg"></div>
