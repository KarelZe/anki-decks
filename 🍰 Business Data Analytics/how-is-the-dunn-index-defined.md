## Note
nid: 1655652560080
model: Basic-02d89
tags: 07_unsupervised_learning_bda
markdown: false

### Front
How is the <b>Dunn Index</b> defined?

### Back
\(\operatorname{Dunn}(C)=\frac{\operatorname{Sep}(C)}{\operatorname{Comp}(C)}\)

Separation and Compactness are defined as:
\(\operatorname{Sep}(C)=\min _{C_{\mathrm{k}} \in C, C_{l} \in C \backslash \mathrm{C}_{k}} \operatorname{Sep}\left(C_{k}, C_{j}\right)=\min _{\mathrm{C}_{\mathrm{k}} \in C, C_{l} \in C \backslash \mathrm{C}_{k} x_{i} \in C_{k}, x_{j} \in C_{l}} d\left(x_{i}, x_{j}\right)\)
\(\operatorname{Comp}(C)=\max _{C_{k} \in C} \operatorname{Comp}\left(C_{k}\right)=\max _{C_{k} \in C} \max _{\mathrm{x}_{\mathrm{i}}, \mathrm{x}_{\mathrm{j}} \in C_{k}} d\left(x_{j}, x_{i}\right)\)
