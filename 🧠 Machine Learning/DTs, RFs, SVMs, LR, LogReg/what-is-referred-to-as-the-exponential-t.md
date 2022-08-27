## Note
nid: 1629610158790
model: Basic-d7a3e-4ce08
tags: checklater, ml::02_linear_classification
markdown: false

### Front
What is referred to as the <b>exponential trick</b> in terms of
<b>conditional probability distributions</b>?
<div>
  Give an example.
</div>

### Back
Say we have a Bernoulli distribution. We have to possible outcomes
of the event c, that depends on x.
<div>
  \(p(c=1 \mid \boldsymbol{x})=\sigma\left(\boldsymbol{w}^{T}
  \boldsymbol{x}+b\right), \quad p(c=0 \mid
  \boldsymbol{x})=1-\sigma\left(\boldsymbol{w}^{T}
  \boldsymbol{x}+b\right)\)
</div>
<div>
  We could then calculate the correct probabilty using the
  exponential trick depending on the value of \(c\) (similar to
  switch):
</div>
<div>
  \(p(c \mid \boldsymbol{x})=p(c=1 \mid \boldsymbol{x})^{c} p(c=0
  \mid \boldsymbol{x})^{1-c}=\sigma\left(\boldsymbol{w}^{T}
  \boldsymbol{x}+b\right)^{c}\left(1-\sigma\left(\boldsymbol{w}^{T}
  \boldsymbol{x}+b\right)\right)^{1-c}\)
</div>
