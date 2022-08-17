## Note
nid: 1651128825797
model: Basic-02d89
tags: 04_regression_bda
markdown: false

### Front
Explain the main idea behind <b>Support Vector Regression</b>.

### Back
In SVR the acceptable error is a parameter for the model. The
objective function is the minimization of the L2 norm of the
parameters. To account for points that cannot be caputred with this
formulation. We can incorporate a penalty on these points.
\(\operatorname{min} \frac{1}{2} || w||^{2}+C
\sum_{i=1}^{n}\left|\xi_{i}\right|\) Constraints:
\(\left|y_{i}-w_{i} x_{i}\right| \leq
\varepsilon+\left|\xi_{i}\right|\) <b>Visualization:</b> <img src= 
"paste-e6d4e775ed59de95dd8e557285b1e90c114634f6.jpg">
