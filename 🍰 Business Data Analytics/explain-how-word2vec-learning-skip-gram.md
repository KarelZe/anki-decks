## Note
nid: 1653498334376
model: Basic-02d89
tags: 10_text_mining_bda
markdown: false

### Front
Explain how <b>Word2Vec Learning</b> (Skip-Gram) works.

### Back
1. <b>Sample words.</b> Select a word pair \(\left(w_{t \pm j} \mid w_{t}\right)\) from corpus
2. <b>Predict.</b> Predict the probability of this pair, given the current embeddings
3. <b>Optimize.</b> Update the embeddings, so that the predicted probability gets higher
