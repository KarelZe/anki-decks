## Note
nid: 1621847272947
model: Basic-d7a3e-4ce08
tags: adv_ml::07_lecture_rf_dc
markdown: false

### Front
Give the <b>intutition</b> and <b>definition</b> for
<b>Bagging</b>.

### Back
<b>Definition:</b>
<div>
  The bagging estimator is made in the following form: \[f_{\text
  {Bagging }}(X)=\frac{1}{B} \sum_{b=1}^{B} \hat{f}_{b}(X)\]
</div>
<div>
  <b>Intuition:</b>
</div>
<div>
  <div>
    Bagging fit a \(\hat{f}_{b}(x)=\hat{\beta}_{b} X_{b}\)
    regression model to \(b\) -th bootstrap samples \(X_{b}\) and
    then bagging take mean of these estimation over a collection of
    bootstrap samples.
  </div>
</div>
