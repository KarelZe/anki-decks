# Note
```
guid: Hn{Pe36/FC
notetype: Basic-d7a3e-4ce08
```

### Tags
```
checklater
ml::08_svm
```

## Front
How can one calculate the width of the <b>margin </b>of a SVM?

## Back
Note that \(\mathbf{w}^{T} \mathbf{x}+b=0\) and \(c\left(\mathbf{w}^{T} \mathbf{x}+b\right)=0\) define the same hyperplane.<div>
</div><div>That means \(c\) can be chosen freely. </div><div>
</div><div>For positive support vectors we set</div><div>
</div><div>\(\mathbf{w}^{T} \mathbf{x}_{+}+b=+1\)
</div><div>
</div><div>For negative support vectors</div><div>
</div><div>\(\mathbf{w}^{T} \mathbf{x}_{-}+b=-1\)
</div><div>
</div><div>The margin is given by:</div><div>
</div><div>\(\frac{\mathbf{w}^{T} \mathbf{x}_{+}+b}{\|\mathbf{w}\|}-\frac{\mathbf{w}^{T} \mathbf{x}_{-}+b}{\|\mathbf{w}\|}=\frac{2}{\|\mathbf{w}\|}\)</div>
