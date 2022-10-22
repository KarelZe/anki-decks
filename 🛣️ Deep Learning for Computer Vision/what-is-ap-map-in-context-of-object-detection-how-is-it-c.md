# Note
```
guid: LEO(!d{6!V
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::05_object_detection
```

## Front
What is <b>AP / mAP</b> in context of <b>object detection</b>? How
is it calculated?

## Back
Average of the precision in the Precision / recall curve. The
precision values chosen to calculate the AP are clculated at fixed
(e. g., at every 0.1 on the recall axis), or at every time the
recall on the curve changes. <b>mAP</b> is the mean of the AP over
all classes. <b>Visualization:</b> <img src="paste-15749689ca2bc6ae8151f8d3b99442157b13c03c.jpg">
