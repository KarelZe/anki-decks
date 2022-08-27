## Note
nid: 1653649253618
model: Basic-02d89-e0e22
tags: bda::08_webcrawling_recommender
markdown: false

### Front
How is the cosine similarity defined? What is the intuition?

### Back
<b>Definition:</b> \[\text { cosine similarity }=S_{C}(A, B):=\cos
(\theta)=\frac{\mathbf{A} \cdot
\mathbf{B}}{\|\mathbf{A}\|\|\mathbf{B}\|}=\frac{\sum_{i=1}^{n}
A_{i} B_{i}}{\sqrt{\sum_{i=1}^{n} A_{i}^{2}} \sqrt{\sum_{i=1}^{n}
B_{i}^{2}}},\] where \(A_{i}\) and \(B_{i}\) are components of
vector \(A\) and \(B\) respectively. <b>Intuition:</b> Correlation
between objects (instead of variables)
