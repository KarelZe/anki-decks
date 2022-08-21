## Note
nid: 1563964556474
model: Basic-66395
tags: 
markdown: false

### Front
How can FullyConv Nets be used for Semantic segmentation? What is an improvement idea?

### Back
Use a ConvNet and then an upsampling layer of deconvolution to
reconstruct an Tensor of the size of the input with depth=#classes.
Learn end to end.
<div>
  Improvement: Use skip-connections for fine-grained information
  from upper layers.
</div>
<div><img src="Screenshot%202019-07-24%20at%2012.35.52.png"></div>
