## Note
nid: 1629433057788
model: Basic-d7a3e
tags: 10_neural_networks, checklater
markdown: false

### Front
What are the <b>advantages / disadvantages</b> of <b>second order
optimization methods</b>?

### Back
<div>
  <div>
    <div>
      <strong>advantages</strong>
    </div>
    <ul>
      <li>no hyperparameters
      <li>no learning rate
      <li>less iterations required
    </ul>
    <div>
      <strong>disadvantages</strong>
    </div>
    <ul>
      <li>Hessian has \(\mathcal{O}(N^2)\) parameters
      <li>Inverse is \(\mathcal{O}(N^3)\) (problematic for large
      \(n\))
    </ul>
  </div>
</div>
