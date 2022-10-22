# Note
```
guid: tYe65%=pL+
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::10_video_self_learning
```

## Front
Explain the idea behind "shuffle and learn"

## Back
<ul>
  <li>Learn temporal order from videos
  <li>Mine short clips with high motion from videos
  <li>Generate positive (in-order) and negative (out-of-order)
  tuples
  <li>Tiplet siamese network (with weight sharing) is used to
  generate feature descriptors
  <li>Concatenated fatures are then classified as "in-order" or
  "out-of-order"
</ul><b>Visualization:</b> <img src="paste-135b84724362ac68ba750de40cb3474051e3af1d.jpg">
