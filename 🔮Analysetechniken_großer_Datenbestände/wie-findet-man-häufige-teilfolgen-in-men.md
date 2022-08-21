## Note
nid: 1608984942630
model: Basic-d7a3e
tags: 08_constrained_ar
markdown: false

### Front
<p>Wie findet man häufige <b>Teilfolgen</b> in Mengen <b>Folgen</b>?</p>

### Back
<p>Ähnlich Apriori. (Join & Test)</p><p>Zunächst werden Kandidaten als Self-Join von \(F_{k-1}\) gebildet. Die Join-Attribute sind die letzen \(k-2\) Elemente der ersten und die ersten \(k-2\) Elemente zweiten Folge.</p><p><b>Beispiel</b>:</p><p><1, 2, 3, 4> <2, 3, 4, 5> → <<b>1</b>, 2, 3, 4, <b>5</b>></p><p>Suffix der ersten Folge und Präfix der zweiten Folge müssen übereinstimmen. Suffix und Präfix muss um jeweils 1 kürzer sein.</p>
