## Note
nid: 1659862330060
model: Basic-02d89
tags: 12_adv_topics_dl_cv
markdown: false

### Front
What is the <b>idea </b>behind <b>domain adaption</b>?

### Back
<ul>
  <li>Train network on image and ground truth data from source
  domain. Use unlabled images from the target domain.
  <li>Assume domains share the same classes.
  <li>Try to find a model that can solve the task for images of the
  target domain.
</ul>
<div>
  <b>Example:</b>
</div>
<div>
  Train on synthetic data e. g., renderings of object and evaluate
  on real data e. g., image.
</div>
