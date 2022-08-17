## Note
nid: 1609353650371
model: Basic-d7a3e
tags: 07_association_rules
markdown: false

### Front
<p>Was ist die Idee des <b>Apriori-B-Algorithmus</b>?</p><p>Welches Ziel verfolgt er? Welches Problem löst er?</p>

### Back
<p><b>Problem</b>: Apriori ist langsam, weil alle möglichen Frequent Itemsets ihrer Größe nach sequenziell erzeugt werden. Man hat exponentielles Wachstum.</p><p><b>Ziel</b>: Weitgehende Vermeidung der Betrachtung von Frequent Itemsets, die nicht maximal sind.</p><p><b>Idee</b>: Man generiert nicht zuerst die einelementigen, dann die zwei-elementigen Frequent Itemsets, sondern durchläuft den Algorithmus in größeren Schritten. Lineare Laufzeit möglich.</p><p><b>Beispiel:</b>
<span>

Aus {1 2 3}, {1 2 4}, {1 2 5}, {1 2 6} wird unmittelbar Kandidat {1 2 3 4 5 6} erzeugt. D. h. es werden Schritte bei der Kandidaten-Generierung ausgelassen.</span></p><p><span></span>Hat sechs-elementiges Itemset Support nicht, generiert man vier-elementige und fünf-elementige Itemsets, die eher Support erreichen können.</p>
