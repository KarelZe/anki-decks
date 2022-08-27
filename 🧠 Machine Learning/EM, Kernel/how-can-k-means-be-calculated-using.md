## Note
nid: 1629780587588
model: Basic-d7a3e-4ce08
tags: ml::06_em_for_dim_reduction
markdown: false

### Front
How can \(k\)<b>-means</b> be calculated using <b>EM</b>?

### Back
<div>
  <div>
    <div>
      Co-variances are always set to 0 (in the limit)
      <strong>E-Step</strong>
    </div>
    <ul>
      <li>repsonsibilites \(q_{ik}\) of nearest cluster \(k\) are
      set to 1, all other values are 0.
    </ul>
    <div>
      <strong>M-Step</strong>
    </div>
    <ul>
      <li>Update the mean is the same.
      <li>Co-Variances are ignored (set close to 0)
    </ul>
  </div>
</div>
