## Note
nid: 1651131953258
model: Basic-02d89
tags: 02_classification_bda
markdown: false

### Front
Define the <b>F1 metric</b>. What is the <b>intuition</b> behind
it?

### Back
\(F_{1}=\frac{2}{\frac{1}{\text { prec. }}+\frac{1}{\text { recall }}}=2 * \frac{\text { prec. } * \text { recall }}{\text { prec. }+\text { recall }}=\frac{T P}{T P+\frac{F N+F P}{2}}\)

Combined measure to take trade-off into account. Harmonic mean of precision and recall.
