## Note
nid: 1652348079014
model: Basic-02d89-e0e22
tags: bda::06_trainining_tuning
markdown: false

### Front
The learning rate can be decayed. Name 4 different approaches.

### Back
<ul>
  <li>\(\alpha_{t}=0.95^{\text{epoch\_num}} \cdot \alpha_{t-1}\)
  <li>\(\alpha_{t}=\frac{1}{1+\text{decay-rate} \cdot
  \text{epoch\_num}} \alpha_{t-1}\)
  <li>Discrete Staircase
  <li>Manual decay
</ul>
