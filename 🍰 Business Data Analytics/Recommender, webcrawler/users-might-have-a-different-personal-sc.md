## Note
nid: 1653652484920
model: Basic-02d89-e0e22
tags: bda::08_webcrawling_recommender
markdown: false

### Front
Users might have a different personal scale when rating. How can this be compensated for in CF?

### Back
<b>Debias / normalize:</b> \[\begin{aligned} &\hat{r}_{u
i}=\bar{r}_{u}+\frac{\sum_{v \in N_{k}(u)} w_{u v}\left(r_{v
i}-\bar{r}_{v}\right)}{\sum_{v \in N_{k}(u)}\left|w_{u v}\right|}\\
&\hat{r}_{u i}=\bar{r}_{u}+\sigma_{u} \frac{\sum_{v \in
N_{k}(u)} w_{u v} \mid \frac{r_{v
i}-\bar{r}_{v}}{\sigma_{v}}}{\sum_{v \in N_{k}(u)}\left|w_{u
v}\right|} \end{aligned}\]
