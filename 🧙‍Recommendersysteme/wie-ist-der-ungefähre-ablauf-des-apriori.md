## Note
nid: 1588100229832
model: Basic-b122e
tags: 02_assoziationsregeln, Algorithmus
markdown: false

### Front
Wie ist der ungefähre Ablauf des <b>Apriori TID Algorithmus</b>?

### Back
<ol><li>Aufbau der 1-elementigen häufigen Itemmengen wie bei Apriori</li>
<li>Parallel zur Durchsuchung der Datenbasis erfolgt der Aufbau einer

Datenstruktur:\(Z_{k}=\left\{<T I D>,\left\{X_{K}\right\}\right\}\), wobei \(TID = \text{eindeutiger Identifier der Transaktion}\) und \(Z_{1} =  \text{gesamte Datenbasis}\) und \(Z_{n} = \text{verbliebene Datenbasis an Transaktionen für } n \text{-elementige Produkt-Kombinationen}\) ist.</li>
<li>Datenstruktur enthält alle Transaktionen, die noch als Grundlage

häufiger Itemmengen in Frage kommen (und diese enthalten).</li>
<li>→ eine Betrachtung mehr von bereits “uninteressant” gewordenen

Transaktionen.</li>
</ol>
