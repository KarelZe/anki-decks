## Note
nid: 1629478691758
model: Basic-d7a3e
tags: 00_klausurfragen, ultra
markdown: false

### Front
What is the key idea behind second order optimization methods? What are their benefits? Why are second order optimization methods usually not applicable for Deep Neural Networks?

### Back
<div>
<div><ul>
<li>To use the second derivative (Hessian) of the objective and directly step towards the minimum of the quadratic approximation.</li>
<li>No learning rate needs to be tuned and they need fewer function evaluations.</li>
<li>Because the Hessian is huge and needs to be inverted.</li>
</ul>
</div></div>
