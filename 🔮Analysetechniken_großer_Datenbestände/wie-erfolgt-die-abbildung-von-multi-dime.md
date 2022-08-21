## Note
nid: 1608984939947
model: Basic-d7a3e
tags: 06_association_rules
markdown: false

### Front
<p>Wie erfolgt die <b>Abbildung </b>von <b>multi-dimensionaler Daten</b> bei <b>Apriori</b>?</p>

### Back
<p>Umwandlung der Datensätze in eindimensionale für die Verwendung
in Apriori:
<p>\(<1, Italian, 50, low > \longrightarrow <1,\{\text {
nat/Ita, age/50, inc/low }\}>\)
<p><b>Intuition</b>:
<p>Man fasst mehrdimensionale Aussagen zu einer Attributmenge mit
ihren jeweiligen Ausprägungen zusammen. Es lässt sich normaler
Apriori anwenden. Man würde zur Kandidatenbildung unterschiedliche
Attribute z. B. nat/ita und inc/high kombinieren. Nicht aber zwei
Mal nat.
