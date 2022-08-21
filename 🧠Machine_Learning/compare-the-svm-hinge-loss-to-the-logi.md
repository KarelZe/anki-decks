## Note
nid: 1628961444564
model: Basic-d7a3e
tags: 08_svm, checklater
markdown: false

### Front
Compare the (SVM) hinge loss to the logistic loss.

### Back
<b>SVM (hinge) loss:</b>
<div>
  \(\max \left(0,1-y_{i} f\left(\boldsymbol{x}_{i}\right)\right)\)
</div>
<div>
  <div>
    <div>
      <ul>
        <li>Outputs -1 or 1
        <li>Estimates maximum margin solution
        <li>Loss contribution is 0 for correct classification
      </ul>
    </div>
  </div>
</div>
<div>
  <b>logistic loss:</b>
</div>
<div>
  \(\log \left(1+\exp \left(-y_{i}
  f\left(\boldsymbol{x}_{i}\right)\right)\right)\)
</div>
<div>
  <div>
    <div>
      <div>
        <ul>
          <li>Outputs probabilities
          <li>Contribution never 0
            <ul>
              <li>Often results in slightly less accurate
              classification
            </ul>
          <li>Diverges faster than hinge loss
            <ul>
              <li>More sensitive to outliers
            </ul>
        </ul>
      </div>
    </div>
  </div>
  <div><img src=
  "paste-cc573063e4172324c94f74334aa8b150d2e734cb.jpg"></div>
</div>
