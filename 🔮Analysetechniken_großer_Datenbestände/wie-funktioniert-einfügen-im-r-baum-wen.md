## Note
nid: 1609430844998
model: Basic-d7a3e
tags: 03_raeumliche_index_strukturen, checklater
markdown: false

### Front
<p>Wie funktioniert einfügen im R-Baum, wenn noch Kapazität vorhanden ist / keine Kapazität mehr im Knoten vorhanden ist?</p>

### Back
<p><b>Kapazität vorhanden:</b> Bei mehreren möglichen Kindern wird
in den Knoten eingefügt, dessen Fläche sich am wenigsten
vergrößert.
<p><b>Keine Kapazität vorhanden:</b> <span style="letter-spacing: 
 0.01071em;">Man muss splitten. Gesplittet wird zwischen Kindern
mit größtem Abstand.</span>
<p>Dann nimmt man Dimension mit größten Abstand zwischen beiden
Objekten und splittet dann entlang im rechten Winkel zur
x-Dimension, wenn x-Dimension am längsten ist. Übrige Objekte
werden derart auf neue Blätter verteilt, dass der Zuwachs zur
Fläche möglichst gering ist.
<p><img src="paste-5bbb15a7ab719cd29726e14281a20f5860c766df.jpg">
