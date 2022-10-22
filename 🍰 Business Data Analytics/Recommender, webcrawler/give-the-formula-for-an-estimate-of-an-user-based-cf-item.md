# Note
```
guid: GA`Hb&.:1/
notetype: Basic-02d89-e0e22
```

### Tags
```
bda::08_webcrawling_recommender
```

## Front
Give the <b>formula</b> for an <b>estimate</b> of an <b>user-based
CF / item-based CF</b>. How do they differ?

## Back
With user-based CF, we had:
\[\hat{r}_{u i}=\bar{r}_{u}+\sigma_{u} \frac{\sum_{v \in N_{k}(u)} w_{u v} \frac{r_{v i}-\bar{r}_{v}}{\sigma_{v}}}{\sum_{v \in N_{k}(u)}\left|w_{u v}\right|}\]
With item-based CF, and \(j\) as another item with \(j \neq i\) we have:
\[\hat{r}_{u i}=\bar{r}_{i}+\sigma_{i} \frac{\sum_{j \in N_{k}(i)} w_{i j} \frac{r_{u j}-\bar{r}_{j}}{\sigma_{j}}}{\sum_{j \in N_{k}(i)}\left|w_{i j}\right|}\]
