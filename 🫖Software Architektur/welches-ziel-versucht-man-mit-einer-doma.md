## Note
nid: 1588930528206
model: Basic-d7a3e
tags: 02_Architectural_Viewpoints, architecture
markdown: false

### Front
Welches Ziel versucht man mit einer Domain-specific Language (DSL) zu erreichen? <div>
</div><div>Zeigen Sie das Konzept von DSL anhand eines Beispiels auf.</div>

### Back
<div><b>Ziel: </b></div><div>Domain-spezifische Sprachen drücken Domänenkonzepte aus, mit dem Ziel die Komplexität bei Modellierung des Systems zu reduzieren.
</div><div><div>
</div><div><b>Funktionsweise:</b></div><div>Ein DSL ist definiert durch eine <b>abstrakte Syntax </b>und ein Mapping zu mindestens einer <b>konkreten Syntax</b>. Die abstrakte Syntax beschreibt dabei die Struktur der Sprache auf eine Art, die unabhängig ihrer Darstellung oder Kodierung ist. Die konkrete Syntax hingegen definiert die textuelle oder grafische Darstellung oder Kodierung von Elementen in abstrakter Syntax.</div><div>
</div><div><b>Beispiel:</b>
Mediastore Beispiel. Abstrakte Syntax: Ein Song hat z. B. Eigenschaften wie Titel, Künstler, Jahr.  Konkrete Syntax: Eine Liste, welche die Informationen in Textform anzeigt, eine grafische Repräsentation als Punkte, ID3 Container für Audiodatei.</div></div>
