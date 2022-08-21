## Note
nid: 1613931064077
model: Basic-b122e
tags: 06_mpi_openmp
markdown: false

### Front
Wie sind <b>Direktive </b>bei <b>OpenMP </b>aufgebaut? Was können Sie enthalten?

### Back
<div>
  <div>
    <ul>
      <li><em>#pragma omp directive [clause[clause]…]</em>
      <li>Angaben zur Parallelisierung von Blöcken
      <li>Unterscheidung zwischen Direktiven für:
        <ul>
          <li>Parallelisierung (for, parallel, sections, single,
          task,…)
          <li>Synchronisation (barrier, critical, master, atomic,…)
          <li>Daten (threadprivate)
        </ul>
    </ul>
  </div>
</div>
