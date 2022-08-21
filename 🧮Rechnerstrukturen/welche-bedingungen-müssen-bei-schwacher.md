## Note
nid: 1617448338574
model: Basic-d7a3e
tags: 11_para_block_prozess
markdown: false

### Front
Welche <b>Bedingungen</b> müssen bei <b>schwacher Konsistenz</b> gelten?

### Back
<div>
<div><ul>
<li>Bevor 
ein Schreib- oder Lesezugriff bezüglich irgendeines anderen Prozessor 
ausgeführt werden darf, müssen alle vorhergehenden 
Synchronisationspunkte erreicht worden sein</li>
<li>Bevor 
eine Synchronisation bezüglich irgendeines anderen Prozessor ausgeführt 
werden darf, müssen alle vorhergehenden Schreib- oder Lesezugriffe 
ausgeführt werden sein</li>
<li>Synchronisationspunkte müssen sequentiell konsistent sein</li>
</ul>
</div></div>
