## Note
nid: 1642578512969
model: Basic-02d89-e0e22
tags: 09_ethics
markdown: false

### Front
Explain how <b>unfairness </b>can be mitigated through <b>in-processing</b>.

### Back
Typically, when training classifiers, we optimize for <b>accuracy </b>(or, equivalently, minimize some loss function).
In fairness-aware ML, we now need to also consider some notion of <b>fairness </b>(e.g., statistical parity) Two common approaches:
<ol><li>Maximizing accuracy subject to fairness constraints \(\max \text { accuracy s.t. unfairness } \leq \epsilon\)</li><li>Maximizing fairness subject to accuracy constraints \(\max \text { fairness s.t. accuracy } \geq \delta\)</li></ol>
