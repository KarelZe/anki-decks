## Note
nid: 1653717771734
model: Basic-02d89
tags: 02_classification_bda
markdown: false

### Front
What is <b>multinomial logistic regression</b>?

### Back
Logistic regression when dependent variable is categorical (=nominal)

Prediction is based on individual logistic regression relative to pivotal class.
\[\begin{array}{r}
\operatorname{Pr}\left(Y_{i}=1\right)=\frac{e^{\beta_{1} \cdot \mathbf{X}_{i}}}{1+\sum_{k=1}^{K-1} e^{\beta_{k}} \cdot \mathbf{X}_{i}} \\
\operatorname{Pr}\left(Y_{i}=2\right)=\frac{e^{\beta_{2} \cdot \mathbf{X}_{i}}}{1+\sum_{k=1}^{K-1} e^{\beta_{k} \cdot \mathbf{X}_{i}}} \\
\cdots \cdots \\
\operatorname{Pr}\left(Y_{i}=K-1\right)=\frac{e^{\beta_{K-1} \cdot \mathbf{X}_{i}}}{1+\sum_{k=1}^{K-1} e^{\beta_{k} \cdot \mathbf{X}_{i}}}
\end{array}\]
