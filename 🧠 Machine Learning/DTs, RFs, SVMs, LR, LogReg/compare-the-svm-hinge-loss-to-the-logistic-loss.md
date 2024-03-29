# Note
```
guid: B{o1Rx)wZQ
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::08_svm
```

## Front
Compare the (SVM) hinge loss to the logistic loss.

## Back
<b>SVM (hinge) loss:</b><div>\(\max \left(0,1-y_{i} f\left(\boldsymbol{x}_{i}\right)\right)\)
</div><div><div><div><ul><li>Outputs -1 or 1</li><li>Estimates maximum margin solution</li><li>Loss contribution is 0 for correct classification</li></ul></div></div></div><div><b>logistic loss:</b></div><div>\(\log \left(1+\exp \left(-y_{i} f\left(\boldsymbol{x}_{i}\right)\right)\right)\)</div><div><div><div><div><ul><li>Outputs probabilities</li><li>Contribution never 0<ul><li>Often results in slightly less accurate classification</li></ul></li>
<li>Diverges faster than hinge loss<ul><li>More sensitive to outliers</li></ul></li></ul></div></div></div><div>
</div><div><img src="paste-cc573063e4172324c94f74334aa8b150d2e734cb.jpg">
</div></div>
