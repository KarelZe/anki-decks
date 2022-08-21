## Note
nid: 1642578116955
model: Basic-02d89
tags: 09_ethics
markdown: false

### Front
How to mitigate <b>algorithmic unfairness</b>?

### Back
<b>Pre-Processing</b>
<ul style=""><li style="">Transform the (training) data with the goal of removing underlying discrimination</li><li style="">For instance, sampling of representative data (e.g., ImageNet discussion \(^{*}\) )...or changing labels, etc.</li></ul><b>In-Processing</b>
<ul><li>Modify learning algorithms to remove discrimination during the training process</li><li>Commonly, either the objective function is adapted, or additional constraints are introduced</li></ul><b>Post-Processing</b>
<ul><li>Any steps undertaken after training fall into this category</li><li>Typically, this involves re-assigning of labels according to some fairness criterion</li><li>Generally, post-processing techniques are only used if both the data and the ML algorithm cannot be altered</li></ul>
