## Note
nid: 1641795681876
model: Basic-02d89
tags: 05_bewertung, checklater
markdown: false

### Front
Wie bestimmt sich der europäische Call mit Basispreis \(X\) in einem Binomialbaum?

### Back
Bewertung einer europäischen Option \(P_{x}\) auf riskantes Wertpapier \(P_{1}\) mit Ausübungswerten in \(T\)
\(P_{x}(T)=a_{i x}\) bei \(i\) Aufwärtsschritten, \(i=0, \ldots, n\)

<b>Europäischer Call</b> mit Basispreis \(X\): \(a_{i x}=\max \left(u^{i} d^{n-i} S-X, 0\right)\)
<b>Europäischer Put</b> mit Basispreis \(X\): \(a_{i x}=\max \left(X-u^{i} d^{n-i} S, 0\right)\)
