# Note
```
guid: h4V<}vq~b3
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::05_object_detection
```

## Front
How does the calculation of the <b>loss</b> of a <b>Region Proposal
Network</b> work?

## Back
Requires a label for each anchor to train the objectness classification.

Positive if IoU with groundtruth or IoU > 0.7. Negative if IoU is < 0.3.

\(L\left(\left\{p_{i}\right\},\left\{t_{i}\right\}\right)=\frac{1}{N_{c l s}} \sum_{i} L_{c l s}\left(p_{i}, p_{i}^{*}\right) +\lambda \frac{1}{N_{r e g}} \sum_{i} p_{i}^{*} L_{r e g}\left(t_{i}, t_{i}^{*}\right)\)

\(N_{cls}\) = batchsize (256), \(N_{reg}\) number of window pos (ca. 2400) \(\lambda = 10\)
