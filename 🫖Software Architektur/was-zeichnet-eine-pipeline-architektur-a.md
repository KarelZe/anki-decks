## Note
nid: 1592228868543
model: Basic-d7a3e
tags: 04_Architectural_Reuse, architecture, architecture_4
markdown: false

### Front
Was zeichnet eine <b>Pipeline-Architektur</b> aus?

### Back
Transformation eines Stroms (<i>Streams</i>) in designierte Tasks.
<div>
</div><div>z. B. ps ef l grep netscape l wc -l</div><div><div>
</div><div>Ein Strom von Daten wird durch eine Reihe von Prozessen hindurch geschleust:
</div></div>
<ul>
<li>Jeder transformiert den Datenstrom in einer Weise</li>
<li>Daten werden konstant in die Pipeline gegeben</li>
<li>Nebenläufig arbeitende Prozesse</li>
</ul><div>Häufig genutzt mit anderen Architekturen wie z. B. Blackboard-Architektur z. B. in Compilern</div><div>
</div><div><b>Skizze:</b></div>
<div><img src="paste-2ca0069caafe3952d1ac8fb1eda358d81eade9e3.jpg">
</div><div>
</div><div><b>Skizze für Pipeline mit Blackboard:</b></div><div><img src="paste-ce15cf736132e9a356782800b452d597b01366f7.jpg">
</div>
