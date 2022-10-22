# Note
```
guid: Ow~pSe6?,^
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::02_classification
```

## Front
Define <b>logistic regression</b>.

## Back
Estimates the probability that an instance belongs to a particular
class. <b>Vectorized form estimator:</b>
\(\hat{p}=h_{\theta}(\mathbf{x})=\sigma\left(\theta^{T}
\mathbf{x}\right)\) where \(\sigma\) the „logistic" (logit) is a
sigmoid function. <b>Prediction model:</b>
\(\hat{y}=\left\{\begin{array}{l}0 \text { if } \hat{p}<0.5 \\ 1
\text { if } \hat{p}>0.5\end{array}\right.\)
