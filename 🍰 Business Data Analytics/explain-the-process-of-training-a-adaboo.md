## Note
nid: 1653719218143
model: Basic-02d89
tags: 02_classification_bda
markdown: false

### Front
Explain the <b>process of training</b> a <b>AdaBoost model</b>.

### Back
<ol>
  <li>Assign each training example a weight > 0
  <li><b>Increase</b> the weights of <b>misclassified examples</b>
  iteratively
  <li><b>Reduce</b> the weights of <b>correctly classifed
  examples</b> iteratively
  <li>Overall hypothesis \(h\) is the composition of the
  differently weighted individual hypotheses \(h_1\) to \(h_4\).
</ol><img src="paste-b400bb82836a5f84a2d00733136ea9366adc1977.jpg">
