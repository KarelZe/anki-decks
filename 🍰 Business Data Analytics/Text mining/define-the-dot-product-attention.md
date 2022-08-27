## Note
nid: 1651237672671
model: Basic-02d89-e0e22
tags: bda::10_text_mining
markdown: false

### Front
Define the dot-product attention.

### Back
\(\operatorname{Attention}(Q, K, V)=\operatorname{softmax}\left(\frac{Q K^{T}}{\sqrt{d_{k}}}\right) V\)

\(Q\) is the query, e.g., the query to search a YouTube video
\(K\) is the key, e.g., video title that is compared to its query
\(V\) is the value, e.g., the videos that are shown to the user
