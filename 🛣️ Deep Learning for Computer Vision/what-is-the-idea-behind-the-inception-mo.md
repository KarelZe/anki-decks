## Note
nid: 1655106371351
model: Basic-02d89
tags: 05_dl_architectures_2_dl_cv
markdown: false

### Front
What is the idea behind the <b>inception module</b>?

### Back
Design a good local network topology ("network within a network")
and then stack the modules on top of each other.
<b>Visualization:</b> <img src= 
"paste-8d17e1d9831beda61b2c0b388a3f06417794c2f6.jpg"> 1x1 conv
creates a linear combination of features / single points 1x1, 3x3,
5x5 ... get concatenated along the feature map.
