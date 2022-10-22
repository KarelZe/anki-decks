# Note
```
guid: wTk~L9Wu7+
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::05_dl_architectures_2
```

## Front
What is the <b>hypothesis</b> between <b>residual blocks</b>? Why
do they work?

## Back
<ul>
  <li>If identity mappings would be optimal (at some late stage in
  network) it would be easier to push the residual to zero, than to
  fit an idenity mapping by a stack of non-linear layers
  <li>Residual blocks should also help if optimal function is close
  to the idenity mapping already (comp. random initialization)
</ul>
