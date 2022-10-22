# Note
```
guid: wE&D5supI(
notetype: Basic-02d89-e0e22
```

### Tags
```
dl_cv::02_basics_nn
```

## Front
Give the formula, how the output of a <b>FFN</b> can be calculated
in the <b>forward pass</b>.

## Back
\(y=f(Wx+b)\) where \(f(\boldsymbol{x})\) e.g.,
\(f(\boldsymbol{x})=max(0,\boldsymbol{x})\). Network with
two-hidden layers: <img src="paste-7b0e4558f401af24c7a63690fdbc7ae55187cfed.jpg">
\(\boldsymbol{x}\) - input layer (pixels) \(\boldsymbol{h}^{1}\) -
first layer hidden units \(\boldsymbol{h}^{2}\) - second layer
hidden units \(\boldsymbol{o}\) - output layer
