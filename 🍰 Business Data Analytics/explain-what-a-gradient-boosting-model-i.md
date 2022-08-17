## Note
nid: 1653739425243
model: Basic-02d89
tags: 04_regression_bda
markdown: false

### Front
Explain what a <b>gradient boosting model</b> is. How is the leaf
value calculated?

### Back
Gradient boosting is a machine learning technique for regression
and classification problems, which produces a prediction model in
the form of an ensemble of weak prediction models, typically
decision trees. The leaf value is what the algorithm uses to
recalculate the residuals, which are then used as a target when
building the next tree. Calculation of leaf value: <img src= 
"paste-67c292d607a42ef17cb662f8d5026b73a3bcf607.jpg">
