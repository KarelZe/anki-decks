## Note
nid: 1637484022921
model: Basic-d7a3e
tags: 05_concept_drift, repeat
markdown: false

### Front
How does the Page-Hinkley Test works?

### Back
This change detection method works by computing the observed values
and their mean up to the current moment. It is a variant of the
cumulative sum. Test for change is based on the Page-Hinkley Test.
The test variable is defined as the cumulative difference between
the observed values and their mean up until the current time. It
will detect a concept drift if the observed mean at some instant is
greater then a threshold value \(\lambda\).
<div>
  <b>Pseudocode</b>:
</div>
<div>
  <img src="paste-761545ec553c8a36247791dc70480660b1e08364.jpg">
  <b>Visualization:</b> <img src= 
  "paste-e17a5cac80038427676ac0264422949385e08f56.jpg"> (left:
  accuracy, left ph statistic)
</div>
