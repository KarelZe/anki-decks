## Note
nid: 1657451467051
model: Basic-02d89
tags: 10_video_self_learning
markdown: false

### Front
Explain the idea behind "shuffle and learn"

### Back
<ul><li>Learn temporal order from videos</li><li>Mine short clips with high motion from videos</li><li>Generate positive (in-order) and negative (out-of-order) tuples</li><li>Tiplet siamese network (with weight sharing) is used to generate feature descriptors</li><li>Concatenated fatures are then classified as "in-order" or "out-of-order"</li></ul>
<b>Visualization:</b>
<img src="paste-135b84724362ac68ba750de40cb3474051e3af1d.jpg">
