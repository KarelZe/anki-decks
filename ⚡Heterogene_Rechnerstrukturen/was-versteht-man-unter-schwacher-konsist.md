## Note
nid: 1612620136217
model: Basic-b122e
tags: 04_koheraenz, 11_para_block_prozess
markdown: false

### Front
Was versteht man unter <strong>schwacher Konsistenz</strong>?

### Back
<ul><li>Lese- und Schreibzugriffe können ihre Ausführung nicht in Programmordnung (out-of-order) beenden, aber es werden Synchronsiationsoperationen verwendet, die eine Ordnung erzwingen, so dass ein synchronisiertes Programm sich so verhält, als wäre der Prozessor sequenziell konsistent.</li><li>Konsistenz nur zum Zeitpunkt einer Synchronisationsoperation.</li><li>Benötigt eine hardware- und softwaremäßige Unterscheidung der Synchronisationsbefehle von Lade- und Speicherbefehlen und eine sequenziell konsistente Implementierung der Synchronisationsbefehle.</li><li>Man ersetzt die die Ordnung der Speicherbefehle durch losere Ordnung der Synchronisationsbefehle. D. h. die Hardware muss nur noch korrekte <b>Verschränkungen</b> der <b>Synchronisationsbefehle</b> umsetzen anstatt Verschränkung aller <b>Zugriffe auf den gemeinsamen Speicher</b>. </li><li><strong>Abgeschwächte Konsistenzmodell</strong> definieren Teilmengen der Ordnungen R → W, R → R, W → W, die sie abschwächen werden.</li></ul>
