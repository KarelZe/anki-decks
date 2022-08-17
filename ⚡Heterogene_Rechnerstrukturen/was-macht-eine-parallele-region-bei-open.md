## Note
nid: 1613917112891
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Was macht eine <b>parallele Region</b> bei <b>OpenMP</b>?

### Back
<div>
  <div>
    <ul>
      <li><em>#pragma omp parallel [clause[clause]…]</em>
      <li>Codeclock, der von allen Threads gleichzeitig ausgeführt
      wird.
        <ul>
          <li>Der Master-Thread hat immer die id=0
          <li>Thread adjustment
            <ul>
              <li>dym. Anpassung von Thread-Teamgrößen nur vor
              Eintritt in parallel region möglich.
            </ul>
          <li>Verschachtlichung paralleler Regionen möglich.
        </ul>
    </ul>
  </div>
</div>
