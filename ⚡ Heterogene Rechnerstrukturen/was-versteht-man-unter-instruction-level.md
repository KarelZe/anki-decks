## Note
nid: 1605038554560
model: Basic-d7a3e-4ce08
tags: 01_vorlesung
markdown: false

### Front
<p>Was versteht man unter <b>Instruction Level Parallelism
(ILP)</b>?

### Back
<p><b>Superskalartechnik</b> ist eine <b>ILP-Architektur.</b>
<p><b>Superskalartechnik:</b> <span>Bei der superskalar-Technik
wird versucht aus einem sequentiellen Befehlsstrom, die Befehle
parallel abarbeiten zu lassen. Solange keine Abhängigkeiten
auftreten, sollte dies eine effiziente Auslastung der
Funktionseinheiten ermöglichen. Doch in der Praxis entstehen sehr
viele Abhängigkeiten (Daten-, Sprung- und
Betriebsmittelabhängigkeiten).</span>
<p>Siehe <b>Skizze</b>:
<p><img src="1VVQMUt1ax4j7Wp8N7mz.png" style="width: 366px;">
<p><b>Warnung:</b> Bei ILP werden also eine Reihe von Anweisungen
desselben Threads eines Prozesses parallelisiert. Etwa erkennt z.
B. die Hardware wenn einzelne Zweige voneinander unabhängig sind.
