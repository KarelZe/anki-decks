## Note
nid: 1625508416991
model: Basic-d7a3e-4ce08
tags: adv_ml::07_lecture_rf_dc
markdown: false

### Front
How is <b>gradient boosting</b> different from <b>random
forests</b>?

### Back
<div>
  <div>
    <ol>
      <li>How trees are built: random forests builds each tree
      independently while gradient boosting builds one tree at a
      time. This additive model (ensemble) works in a forward
      stage-wise manner, introducing a weak learner to improve the
      shortcomings of existing weak learners.
      <li>Combining results: random forests combine results at the
      end of the process (by averaging or “majority rules”) while
      gradient boosting combines results along the way.
    </ol>
  </div>
</div>
