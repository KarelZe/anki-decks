## Note
nid: 1636444640280
model: Basic-d7a3e
tags: 04_deployment, repeat
markdown: false

### Front
Name 3 <b>challenges</b> in the <b>deployment</b> of a <b>machine
learning model</b>.

### Back
<ul>
  <li><strong>multiple languages</strong> (Python, R, Scala) are
  routinely used, even for different parts of the same model. ->
  <b>APIs</b>
  <li><strong>Parallel GPU Usage:</strong> Deep Learning often
  requires a lot parallelization, like what’s offered by GPUs.
  These are rarely part of your existing core infrastructure.
  <b>-> Cloud</b>
  <li><strong>Unpredictable Costs:</strong> Usage of Machine
  Learning models for inference can follow a spiked an
  unpredictable pattern, making cost-efficient scaling difficult.
  -> Serverless
</ul>
