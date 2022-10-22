# Note
```
guid: N@#A&A(l:s
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::07_image_seg
```

## Front
Explain what <b>Conditional Random Fields</b> do.

## Back
Smooth noisy segmentation maps. Can be applied after interpolated
network output. Not part of End-to-End networks. Employs energy
function for label assignments \(x\). \(E(x)=\sum_{i}
\theta_{i}\left(x_{i}\right)+\sum_{i j} \theta_{i j}\left(x_{i},
x_{j}\right)\) \(\theta_{i}\left(x_{i}\right)=-\log
P\left(x_{i}\right)\) \(\theta_{i j}\left(x_{i},
x_{j}\right)=\mu\left(x_{i}, x_{j}\right)\left[w_{1} \exp
\left(-\frac{\left\|p_{i}-p_{j}\right\|^{2}}{2
\sigma_{\alpha}^{2}}-\frac{\left\|I_{i}-I_{j}\right\|^{2}}{2
\sigma_{\beta}^{2}}\right)+w_{2} \exp
\left(-\frac{\left\|p_{i}-p_{j}\right\|^{2}}{2
\sigma_{Y}^{2}}\right)\right]\) <b>Example:</b> <img src="paste-3868ad63d9ddf59901f7129fabff1a46018a6c66.jpg">
