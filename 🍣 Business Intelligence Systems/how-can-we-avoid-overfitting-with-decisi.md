## Note
nid: 1635263269689
model: Basic-d7a3e
tags: 06_decision_tree
markdown: false

### Front
How can we avoid <b>overfitting</b> with <b>decision trees</b>?

### Back
<div><strong>Pre-pruning</strong></div><ul><li>Stop growing a branch when information becomes unreliable</li><li>Halt tree construction early</li></ul><div><strong>Post-pruning</strong></div><ul><li>Grow full tree, then discard unreliable parts</li></ul><div><strong>Test Set</strong></div><ul><li>Use a set of testing data different from the training data to decide which is the “best pruned tree"</li></ul>
