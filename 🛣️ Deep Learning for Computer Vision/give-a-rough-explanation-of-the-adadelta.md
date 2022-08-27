## Note
nid: 1651485264307
model: Basic-02d89-e0e22
tags: dl_cv::02_basics_nn
markdown: false

### Front
Give a rough explanation of the <b>Adadelta optimizer</b>.

### Back
<ul>
  <li>Extension of Adagrad with less aggressive learning rate decay
  <li>Adadelta restricts the window of accumlated past gradients to
  some fixed size \(\boldsymbol{w}\)
</ul>
