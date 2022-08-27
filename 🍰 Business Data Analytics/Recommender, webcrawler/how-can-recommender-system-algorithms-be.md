## Note
nid: 1651134332011
model: Basic-02d89-e0e22
tags: bda::08_webcrawling_recommender
markdown: false

### Front
How can <b>Recommender System algorithms</b> be evaluated?

### Back
<ul>
  <li>Separate the available ratings into a training and test set
  (or cross-validation folds)
  <li>Train a model on the training ratings
  <li>Evaluate the predictions on the test ratings in \(T\), e.g.,
  using root mean squared error (RMSE)
  <li>\(R M S E=\sqrt{\frac{1}{|T|} \sum_{(u, i) \in T}\left(r_{u
  i}-\hat{r}_{u i}\right)^{2}}\)
</ul><b>Visualization:</b> <img src= 
"paste-e6ea3f2fad87655be103b4c48445019e1990cf28.jpg">
