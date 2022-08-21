## Note
nid: 1653738536073
model: Basic-02d89
tags: 04_regression_bda
markdown: false

### Front
What is the intuition behind the \(R^2\)? How is it defined.

### Back
\[R^{2}=\frac{T S S-R S S}{T S S}=1-\frac{R S S}{T S S}\] with \(T
S S=\sum_{i=1}^{n}\left(y_{i}-\bar{y}\right)^{2}\) and \(R S
E=\sqrt{\frac{1}{n-p-1} R S S}\) <b>Intuition:</b>
<ul>
  <li>R-Squared measures the proportion of variance explained,
  <li>Takes values in \([0 ; 1]\) whereas larger values are better.
</ul>
