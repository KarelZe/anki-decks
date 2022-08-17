## Note
nid: 1563892243774
model: Basic-66395
tags: 
markdown: false

### Front
What is the motivation of Resnet? How can it be improved?

### Back
Deeper models should perform better, but are hard to optimize.
<div>
  Solution: Use layers to fit residual mapping instead of direct
  mapping.
</div>
<div><img src="Screenshot%202019-07-23%20at%2016.34.36.png"></div>
<div>
  Also use bottleneck 1x1 conv to reduce #operations for deeper
  Resnets (50+ layers)
</div>
