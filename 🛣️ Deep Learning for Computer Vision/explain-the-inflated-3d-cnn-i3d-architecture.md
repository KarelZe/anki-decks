# Note
```
guid: FbI?n8][fz
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::10_video_self_learning
```

## Front
Explain the <b>Inflated 3D CNN (I3D) architecture</b>.

## Back
Extend the Inception-V1 architecture to 3D for action recognition.
Filters and pooling kernels inflated with the time dimension (\(NxN
\rightarrow NxNxNm\)) Pre-training on Image-Net possible: Learned
weights of 2-D filters repeated \(N\) times along the time
dimension. Adjust the Inception V1 architecture with some minor
modifications such as that the first two max-pooling layers do not
perform temporal pooling. <b>Visualization:</b> <img src="paste-3fc9584a60a159e89c61a13e0a7dc4ad12c04435.jpg"> <img src="paste-7964a852ce1952b44ca61e35a80a4c815de3e014.jpg">
