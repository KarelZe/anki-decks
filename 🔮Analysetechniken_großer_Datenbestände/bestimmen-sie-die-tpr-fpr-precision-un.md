## Note
nid: 1633600545061
model: Basic-d7a3e
tags: 05_evaluation, checklater, ultra
markdown: false

### Front
Bestimmen Sie die TPR, FPR, Precision und Recall für folgenden Fall:<div>
</div><div>Man hat 10 samples in Testset. 9 Samples und positiv und 1 negativ. Classifier sagt immer Mehrheitsklasse vorher.</div>

### Back
TP = 9, FP = 1, TN = 0, FN = 0
<div>
  Precision = 0.9 ("gut")
</div>
<div>
  Recall = 1.0 ("gut")
</div>
<div>
  TPR = TP / (TP + FN) = 1.0 ("gut")
</div>
<div>
  FPR = FP / (FP + TN) = 1.0 ("schlecht")
</div>
