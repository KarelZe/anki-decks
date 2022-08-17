## Note
nid: 1620318316722
model: Basic-b122e
tags: 05_vorlesung
markdown: false

### Front
Why does \(k\)-fold Cross-Validation fail in finance?

### Back
Observations in finance are often not an IID process. Leakage takes place when the training set contains information that also appears in the testing set.<div>
</div><div><b>Example:</b></div><div>
</div><div>By placing \(t\) and \(t+1\) in different sets, information is leaked:
When a classifier is first trained on \(\left(X_{t}, Y_{t}\right)\), and then it is asked to predict \(E\left(Y_{t+1} \mid X_{t+1}\right)\) based on an observed \(X_{t+1}\), this classifier is more likely to achieve \(Y_{t+1}=E\left(Y_{t+1} \mid X_{t+1}\right)\) even if \(X\) is an irrelevant feature.
</div>
