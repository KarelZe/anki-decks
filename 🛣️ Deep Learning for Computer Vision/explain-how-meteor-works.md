## Note
nid: 1656317051636
model: Basic-02d89-e0e22
tags: dl_cv::misc
markdown: false

### Front
Explain how <b>METEOR</b> works?

### Back
Combine precision and recall. <b>Example:</b> Hyp: on the mat sat
the cat Ref: the cat sat on the mat Unigram precision = 1, recall =
1 \(F_{\text{mean}} = (10\times P \times R) / (R + 9P) = 1\)
\(\text{METEOR} = (1- \text{mapping penalty}) \times
F_{\text{mean}}\)
