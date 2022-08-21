## Note
nid: 1659870408479
model: Basic-02d89
tags: 12_adv_topics_dl_cv
markdown: false

### Front
How does zero-shot learning work formally? Explain.

### Back
<b>Task:</b> Recognize classes that were never seen before by
leveraging a semantic embedding. <b>Given:</b> Visual data
\(x^{\text {seen }} \in X\) corresponding to the labels \(y^{\text
{seen }} \in Y\) Semantic embedding \(\varphi(y): Y \rightarrow S\)
each class has an associated semantic embedding. <b>Goal:</b>
Recognize visual samples \(x^{u n s e e n} \in X\) corresponding to
classes \(y^{\text {unseen }} \in\) \(Y\) under the Zero-Shot
condition: \[y^{\text {unseen }} \cap y^{\text {seen }}=\emptyset\]
