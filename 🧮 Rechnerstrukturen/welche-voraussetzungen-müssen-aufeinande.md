## Note
nid: 1628400916375
model: Basic-d7a3e-4ce08
tags: checklater, klausur
markdown: false

### Front
Welche Voraussetzungen müssen aufeinanderfoglende Befehle erfüllen, um die Parallelität in Pipelines optimal zu nutzen?

### Back
<div>
<div><ul>
<li>Es 
müssen genügend Ressourcen für alle Befehle vorhanden sein, oder 
umgekehrt: Die Befehlskombination darf die vorhandenen Ressourcen nicht 
überbelegen</li>
<li>Die Operanden müssen verfügbar sein, das heißt, die Befehle dürfen untereinander keine echten Datenabhängigkeiten zeigen.</li>
<li>Die Befehle dürfen den Befehlszähler nicht verändern</li>
</ul>
</div></div>
