## Note
nid: 1655652118315
model: Basic-02d89
tags: 07_unsupervised_learning_bda
markdown: false

### Front
How is the <b>Silhouette coefficient</b> defined?

### Back
Silhouette of object \(o\) in cluster \(A\) is defined as
\(S(o)=\left\{\begin{array}{cl}0 & \text { if } o \text { single
element of } A \text { is } \\ \frac{\operatorname{dist}(B,
o)-\operatorname{dist}(A, o)}{\max (\operatorname{dist}(A, o),
\operatorname{dist}(B, o))} & \text { else }\end{array}\right.\)
The distance of object o to cluster \(A\) is given by
\[\operatorname{dist}(A, o)=\frac{1}{n_{A}-1} \sum_{a \in A, a \neq
0} \operatorname{dist}(a, o)\] The distance of object o to closest
cluster \(B\) is given by \[\operatorname{dist}(B, o)=\min _{C \neq
A}\left(\frac{1}{n_{C}} \sum_{c \in C} \operatorname{dist}(c,
o)\right)\] <b>Visualization:</b> <img src= 
"paste-3497e11d80e28cb882ef46739ec1888bcec753e3.jpg">
