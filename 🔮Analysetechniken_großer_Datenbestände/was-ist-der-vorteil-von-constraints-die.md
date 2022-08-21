## Note
nid: 1608984948793
model: Basic-d7a3e
tags: 08_constrained_ar
markdown: false

### Front
Was ist der Vorteil von Constraints, die succinct sind?

### Back
<p>Anders als beim Apriori-Algorithmus muss nicht das Itemset mit drei Produkten erzeugt werden, sondern es erfolgt einmal das Support Counting. Das spart Rechenaufwand.
</p><p style="font-weight:400;letter-spacing:normal;text-indent:0px;text-transform:none;white-space:normal;word-spacing:0px"><strong>Beispiel:</strong> Man hat das Constraint, dass der Typ "Non-Food" sein soll. Aber es gibt nur 3 Produkte die diesen Typ haben. Kandidaten, die das Constraint nicht erfüllen werden gar nicht erst erzeugt.</p><p></p>
