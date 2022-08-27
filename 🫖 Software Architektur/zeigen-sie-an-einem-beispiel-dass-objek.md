## Note
nid: 1637404362139
model: Einfach-996eb
tags: 02_Architectural_Viewpoints, architecture
markdown: false

### Vorderseite
Zeigen Sie an einem Beispiel, dass Objektorientierung keine Komponenten sind.

### Rückseite
<img src="paste-e538c6dbbb25b3b1af7051ec6f3441a2b9514f22.jpg">
<div>
  Prblematisch ist Überschreiben einer methode. B erbt von A.
  Methode in A ruft n() auf. B überschreibt n(). Es ist dann für
  den Methodenaufruf von m nicht klar, dass dieser von dem
  überschriebenen n() abhängt. Überschreiben von Methoden ist keine
  Blackbox-Nutzung mehr. Man hätte dann Whitebox Nutzung, weil man
  Code der Oberklasse kennen muss.
</div>
