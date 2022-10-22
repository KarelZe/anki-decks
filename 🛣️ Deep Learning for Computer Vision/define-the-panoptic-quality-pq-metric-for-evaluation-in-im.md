# Note
```
guid: fbTv}yweIq
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::07_image_seg
```

## Front
Define the <b>Panoptic Quality (PQ) metric</b> for evaluation in
<b>image segmentation</b>.

## Back
The Panoptic Quality (PQ) metric which measures segmentation
quality and recognition quality in a unified approach \[ P
Q=\frac{\sum_{(p, g) \in T P} \operatorname{IoU}(p, g)}{|T
P|+\frac{1}{2}|F P|+\frac{1}{2}|F N|}=\frac{\sum_{(p, g) \in T P}
\operatorname{IoU}(p, g)}{|T P|} \times \frac{|T P|}{|T
P|+\frac{1}{2}|F P|+\frac{1}{2}|F N|} \] Segmentation quality is
the mean loU of the True Positive masks. Recognition quality is the
F1 score of the predicted masks. A predicted mask and a ground
truth mask are a True Positive if their IoU is strictly greater
than 0.5. The 0.5 loU threshold guarantees a unique matching.
<b>Visualization:</b> <img src="paste-93e736118e3ab78ef77064598cce24c4cf4afdd0.jpg">
