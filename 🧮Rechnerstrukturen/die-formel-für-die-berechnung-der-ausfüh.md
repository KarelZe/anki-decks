## Note
nid: 1628399181445
model: Basic-d7a3e
tags: checklater, klausur
markdown: false

### Front
Die Formel für die Berechnung der Ausführungszeit einer sequentiellen Pipeline lautet:<div>\(T_{seq}=n * k\)
</div><div>
</div><div>Worin liegt die Formel zur Berechnung der sequentiellen Ausführungszeit begründet?</div>

### Back
Die Formel begründet sich durch die angenommene zeitliche
Verarbeitungsdauer in einem Prozessor <b>ohne Pipelining</b>, es
handelt sich lediglich um ein Modell.
<div>
  Jeder Befehl müsste die gleichen Gatter und Flip-Flops innerhalb
  eines Taktes durchlaufen (mit Ausnahme der Pipeline-Register),
  weshalb die Taktperiode etwa \(k\) mal so lang sein müsste
  aufgrund der gleichen Verzögerung der einzelnen Elemente.
</div>
