## Note
nid: 1637483709789
model: Basic-d7a3e
tags: 05_concept_drift, repeat
markdown: false

### Front
Explain how the ADWIN algorithm works.

### Back
ADWIN is an adaptive sliding window algorithm for detecting change,
and keeping updated statistics about a data stream. ADWIN allows
algorithms not adapted for drifting data, to be resistant to this
phenomenon. The general idea is to keep statistics from a window of
variable size while detecting concept drift.
<div>
  It uses a detection window \(W\) which interatively adapts.
  Whenever two large (sub) windows of \(W\) exhibit distinct enough
  means, the algortihm drops older elements.
</div>
<div>
  The threshold \(\varepsilon\) is defined by the Hoeffding bound.
</div>
<div>
  <b>Pseudo Code:</b>
</div>
<div>
  <img src="paste-614fe4118efe86a159a03a8b3f1a04f0dea9d3fb.jpg">
  <b>Visualization</b>: <img src= 
  "paste-7efa4b6272ef88bc7693aba6a6fee2fa7fc8666b.jpg"> (right:
  window builds up)
</div>
