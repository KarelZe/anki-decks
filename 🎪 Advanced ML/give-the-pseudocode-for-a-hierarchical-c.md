## Note
nid: 1620498435127
model: Basic-d7a3e-4ce08
tags: adv_ml::08_clustering
markdown: false

### Front
Give the pseudocode for a <b>hierarchical clustering algorithm</b>.

### Back
<div>
  <div>
    <ol>
      <li>Begin with \(n\) observations and a measure (such as
      Euclidean distance) of all the \(\left(\begin{array}{c}n \\
      2\end{array}\right)=n(n-1) / 2\) pairwise dissimilarities.
      Treat each observation as its own cluster.
      <li>For \(i=n, n-1, \ldots, 2\)
    </ol>
    <ul>
      <li>Examine all pairwise inter-cluster dissimilarities among
      the \(i\) clusters and identify the pair of clusters that are
      least dissimilar (that is, most similar). Fuse these two
      clusters. The dissimilarity between these two clusters
      indicates the height in the dendrogram at which the fusion
      should be placed.
      <li>Compute the new pairwise inter-cluster dissimilarities
      among the \(i-1\) remaining clusters.
    </ul>
  </div>
</div>
