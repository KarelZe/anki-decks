## Note
nid: 1609353651460
model: Basic-d7a3e
tags: 07_association_rules
markdown: false

### Front
<p>Was ist die Idee von <b>Projected Databases</b> bei <b>FP-Trees</b>?</p>

### Back
<p>Abhängig von der Verteilung der Daten, kann FP-Tree nicht in Hauptspeicher passen.</p><p>Man partioniert die Menge von <b>Transaktionen / Datenbestand</b> mit dem Kriterium: "das letzte Element, das in der Transaktion jeweils enthalten ist". Z. B. alle Transaktionen die auf \(p\) enden, heißt \(p\)-projected database. Alle die auf \(m\) enden, heißt \(m\)-projected database.</p><p>Man baut FP Tree nur für Transaktionen auf, die \(p\) (seltenstes Item)  enden. Man bestimmt dann Frequent Items. Danach löscht man Vorkommen von \(p\) aus FP-Tree und Headertabelle. Danach baut man \(m\)-projected database (2. seltenstes Item) auf. Man fügt dann \(m\)-Transaktionen in gekürzten (weil \(p\) weggeschnitten wurde) FP-Tree ein. Man bestimmt dann alle Frequent Itemsets, die \(m\), aber nicht \(p\) enthalten. Man fährt so fort.</p>
