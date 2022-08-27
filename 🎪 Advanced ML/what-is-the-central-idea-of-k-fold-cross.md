## Note
nid: 1620317326538
model: Basic-d7a3e-4ce08
tags: 05_vorlesung
markdown: false

### Front
What is the central idea of <b>K-Fold Cross-Validation</b>?

### Back
Idea is to randomly divide the data into \(K\) equal-sized parts.
We leave out part \(k\), fit the model to the other \(K-1\) parts
(combined), and then obtain predictions for the left-out \(k\)-th
part. This is done in turn for each part \(k=1,2, \ldots, K\), and
then the results are combined.
<div><img src=
"paste-abf545095be98300a35bd200956e115cae7fd658.jpg"></div>
